
# nxphuong.github.io (NXP — scaffold theo chuẩn, không dính thương hiệu MXD)

- GA4: **G-2RX0F54604** (analytics.js trước affiliate)
- Affiliate rewrite: dùng *deep_link base* (đã có `sub4=oneatweb`) + tự thêm `url=<origin>&utm_*&sub1=<sku>&sub2=<merchant>`
- Canonical tuyệt đối (`https://nxphuong.github.io`), JSON-LD Product ở `g.html?sku=`
- Ảnh: `/assets/img/products/<sku>.webp`, danh mục `/assets/img/categories`
- SW: HTML **network-first**, assets **stale-while-revalidate**

Triển khai:
1) Tạo repo **nxphuong.github.io** (Public) → upload ZIP vào root → commit
2) Mở **https://nxphuong.github.io**
