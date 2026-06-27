# GAMEHAIVL GitHub Pages - Minecraft 1.21.132

Bộ code tĩnh tối ưu cho GitHub Pages, được dựng lại từ trang gốc WordPress/Flatsome của GAMEHAIVL.

## File chính

- `index.html`: trang chính có thể chạy ngay trên GitHub Pages.
- `minecraft-1-21-132/index.html`: URL dạng thư mục để mô phỏng slug gốc.
- `404.html`: trang lỗi thân thiện, tránh trắng trang.
- `.nojekyll`: giúp GitHub Pages không xử lý sai file tĩnh.
- `robots.txt` và `sitemap.xml`: hỗ trợ SEO cơ bản.

## Điểm đã tối ưu

- Không còn phụ thuộc PHP, WordPress, jQuery, wpDiscuz, Flatsome JS hoặc admin bar.
- CSS/JS được nhúng trực tiếp để tránh lỗi load asset trên GitHub Pages.
- Toàn bộ ảnh dùng URL tuyệt đối `https://gamehaivl.com/...`, không còn đường dẫn `/wp-content/...` bị lỗi trên GitHub.
- Có meta SEO, Open Graph, Twitter Card, canonical và JSON-LD.
- Có Article schema, SoftwareApplication schema, BreadcrumbList, FAQPage và Organization.
- Responsive mobile, có menu mobile, TOC, FAQ, sidebar và related posts.

## Cách deploy

1. Giải nén file ZIP.
2. Upload toàn bộ file bên trong thư mục lên root repo GitHub.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from branch**.
5. Chọn branch `main` và thư mục `/root`.
6. Đợi GitHub Pages build xong rồi mở URL.

> Lưu ý: `index.html` phải nằm ngay ngoài cùng repo. Không upload nguyên thư mục bọc bên ngoài nếu không GitHub Pages sẽ không thấy file trang chủ.
