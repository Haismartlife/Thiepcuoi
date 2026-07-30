CÁCH THAY ẢNH THẬT:

Code đã trỏ sẵn tới các file .jpg rồi, bạn KHÔNG cần sửa gì trong index.html
(trừ ảnh og-cover.jpg — xem lưu ý riêng bên dưới) — chỉ cần:

1. Chuẩn bị ảnh cưới thật của bạn.
2. Đặt đúng tên file:
   - Ảnh đại diện (vòng tròn ở đầu thiệp): couple.jpg
   - 4 ảnh trong album: gallery-1.jpg, gallery-2.jpg, gallery-3.jpg, gallery-4.jpg
   - Ảnh hiện khi CHIA SẺ LINK qua Zalo/Messenger/Facebook: og-cover.jpg
3. Thả vào đúng thư mục này (assets/images/), ĐÈ LÊN file placeholder cùng tên.
4. Deploy lại lên Vercel là xong.

Gợi ý kích thước:
- couple.jpg, gallery-X.jpg: ảnh vuông (tỉ lệ 1:1), tối thiểu 800x800px.
- og-cover.jpg: ảnh NGANG, đúng tỉ lệ 1200x630px (hoặc gần đúng, ví dụ
  1200x628) — đây là kích thước chuẩn cho ảnh preview khi dán link,
  ảnh vuông hoặc dọc sẽ bị cắt xấu khi hiện trên Zalo/Facebook/Messenger.

⚠️ RIÊNG VỚI og-cover.jpg — có thêm 1 bước:
Ảnh này được khai trong link TUYỆT ĐỐI ở đầu file index.html (2 dòng
og:image và twitter:image), dạng:
   https://thiep-cuoi-smartshop.vercel.app/assets/images/og-cover.jpg
Nếu sau này bạn đổi sang domain khác (vd domain riêng .vn của bạn), phải
sửa lại đúng domain mới trong 2 dòng đó, nếu không ảnh sẽ không hiện được
khi chia sẻ link (dù bạn đã đổi ảnh og-cover.jpg đúng cách).
