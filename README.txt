# Patch: Danh mục "Thời trang"

Files:
- /store/thoi-trang.html  (hub)
- /assets/img/categories/thoi-trang.webp  (icon)
- /store.html  (đã chèn tile mẫu; REPLACE nếu file của bạn chưa chỉnh gì thêm)
- /SITEMAP-INSERT-thoi-trang.txt (block XML để thêm vào sitemap)

Commit gợi ý:
1) feat(layout): add Thời trang hub at /store/thoi-trang.html
2) feat(layout): add Thời trang tile linking to /store/thoi-trang.html in store.html
3) chore(seo): update sitemap.xml with /store/thoi-trang.html (lastmod=2025-10-29)

Nếu store.html của bạn đã chỉnh trước đó, đừng replace — chỉ chèn dòng sau vào grid:

<li><a class="category-tile" href="/store/thoi-trang.html"><img src="/assets/img/categories/thoi-trang.webp" alt="Thời trang — MXD" width="600" height="400"><span>Thời trang</span></a></li>
