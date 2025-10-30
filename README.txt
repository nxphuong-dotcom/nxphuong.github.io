# nxp.github.io — scaffold (brand riêng; no 'mxd' text)

Cấu hình nhanh:
- assets/aff-engine.js → điền ISCLIX.pub_id, ISCLIX.camp_id
- assets/site.config.json → tel/zalo/facebook/email (để trống sẽ ẩn nút)
- assets/analytics.js → GA4 (nếu dùng)

Triển khai:
1) Upload toàn bộ lên repo nxphuong.github.io (nhánh main).
2) Settings → Pages → Deploy from a branch → main / / → Save
3) Mở https://nxphuong.github.io

Commit gợi ý:
chore(init): scaffold nxp brand
feat(layout): home, store, 3 hubs, contact, floating buttons
feat(product): product page + affiliate rewrite (isclix)
feat(data): 2 SKU demo mỗi danh mục
chore(seo): sitemap, robots, .nojekyll
