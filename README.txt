# Patch: Danh mục "Mỹ phẩm"
Files:
- /store/my-pham.html
- /assets/img/categories/my-pham.webp
- /store.html (đã chèn tile Mỹ phẩm)
- /SITEMAP-INSERT-my-pham.txt

Commit messages gợi ý:
1) feat(layout): add Mỹ phẩm hub at /store/my-pham.html
2) feat(layout): add Mỹ phẩm tile linking to /store/my-pham.html in store.html
3) chore(seo): update sitemap.xml with /store/my-pham.html (lastmod=2025-10-29)

Nếu store.html đã được chỉnh trước đó, chỉ chèn tile sau vào grid:
<li><a class="category-tile" href="/store/my-pham.html"><img src="/assets/img/categories/my-pham.webp" alt="Mỹ phẩm — MXD" width="600" height="400"><span>Mỹ phẩm</span></a></li>
