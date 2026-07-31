CÁCH THAY ẢNH THẬT:

Code đã trỏ sẵn tới các file .jpg rồi, bạn KHÔNG cần sửa gì trong index.html
— chỉ cần đặt đúng tên file, thả vào đúng thư mục này (đè lên placeholder):

  - couple.jpg          → ảnh đại diện vòng tròn ở đầu thiệp
  - gallery-1.jpg ... gallery-6.jpg → 6 ảnh trong Album ảnh cưới
  - banner-1.jpg        → ảnh lớn full-width (mục "Khoảnh khắc của chúng tôi",
                           nằm giữa phần Lời mời và phần Sự kiện)
  - countdown-bg.jpg    → ảnh nền mờ phía sau mục "Đếm ngược"
  - og-cover.jpg        → ảnh hiện khi CHIA SẺ LINK qua Zalo/Messenger/Facebook

Sau khi thay xong, deploy lại lên Vercel là thấy ảnh mới ngay.

GỢI Ý KÍCH THƯỚC:
  - couple.jpg, gallery-X.jpg : ảnh vuông (1:1), tối thiểu 800x800px.
    Bố cục Album: ảnh 1 và ảnh 4 hiển thị Ô LỚN (bên trái), ảnh 2+3 và
    5+6 xếp chồng vừa khít bên phải — cạnh các ô luôn thẳng hàng nhau,
    không bị so le. Nên chọn 2 tấm đẹp/nét nhất cho vị trí ảnh 1 và 4.
  - banner-1.jpg : ảnh NGANG, tỉ lệ khoảng 16:7 (ví dụ 1400x640px),
    ảnh vuông/dọc sẽ bị cắt hai bên.
  - countdown-bg.jpg : ảnh NGANG, tỉ lệ khoảng 14:9 (ví dụ 1400x900px).
    Ảnh này sẽ bị PHỦ MỘT LỚP TRẮNG MỜ lên trên (để số đếm ngược vẫn đọc
    rõ), nên chọn ảnh không quá nhiều chi tiết ở giữa khung hình.
  - og-cover.jpg : ảnh NGANG, đúng tỉ lệ 1200x630px.

⚠️ RIÊNG VỚI og-cover.jpg — cần thêm 1 bước:
Ảnh này được khai trong link TUYỆT ĐỐI ở đầu file index.html (2 dòng
og:image và twitter:image). Nếu đổi sang domain khác, phải sửa lại
đúng domain mới trong 2 dòng đó, nếu không ảnh sẽ không hiện khi chia
sẻ link (dù đã đổi ảnh og-cover.jpg đúng cách).
