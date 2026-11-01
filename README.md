# ✨ Fileora – All-in-One PDF Studio

> Một không gian xử lý tài liệu hiện đại, nơi mọi nội dung có thể trở thành PDF.

**Fileora** là website hỗ trợ chuyển đổi tài liệu sang PDF, ghép ảnh thành PDF và tạo tài liệu PDF từ hình ảnh hoặc văn bản. Dự án hướng đến trải nghiệm đơn giản, trực quan, hiện đại và dễ sử dụng.

---

## 1. Giới thiệu dự án

- **Tên dự án:** Fileora
- **Tên đầy đủ:** Fileora – All-in-One PDF Studio
- **Người phát triển:** Phan Văn Minh Đức
- **Địa điểm:** Nghệ An, Việt Nam
- **Loại dự án:** Web Application
- **Ngôn ngữ giao diện:** Tiếng Việt
- **File giao diện chính:** `index.html`

### Mục tiêu

Xây dựng một công cụ PDF đa năng, cho phép người dùng xử lý tài liệu ngay trên website mà không cần cài đặt phần mềm phức tạp.

Fileora tập trung vào ba mục tiêu:

1. Chuyển đổi các định dạng tệp được hỗ trợ sang PDF.
2. Ghép ảnh, nhập văn bản và sắp xếp nội dung để tạo PDF.
3. Mang đến trải nghiệm sử dụng đẹp mắt, mượt mà và dễ tiếp cận.

---

## 2. Các chức năng chính

### 2.1. Convert to PDF – Chuyển đổi sang PDF

Cho phép người dùng tải tệp từ máy tính và chuyển đổi sang PDF.

Các định dạng dự kiến hỗ trợ:

| Nhóm | Định dạng |
|---|---|
| Word | DOC, DOCX, ODT |
| Excel | XLS, XLSX, CSV, ODS |
| PowerPoint | PPT, PPTX, ODP |
| Hình ảnh | JPG, JPEG, PNG, WEBP, BMP, GIF |
| Văn bản | TXT, RTF, HTML |
| Dữ liệu | JSON, XML |

Tính năng:
- Chọn tệp từ máy tính.
- Kéo và thả tệp.
- Hiển thị tên, dung lượng và định dạng.
- Xóa hoặc thay thế tệp.
- Hiển thị tiến trình chuyển đổi.
- Xử lý lỗi khi gặp định dạng không hỗ trợ.
- Preview PDF sau khi chuyển đổi.
- Phóng to, thu nhỏ và chuyển trang.
- Tải PDF xuống máy tính.

**Yêu cầu:** Chỉ thông báo thành công khi thực sự tạo được tệp PDF hợp lệ.

### 2.2. Image & Document Studio – Ghép ảnh và tạo tài liệu PDF

Đây là khu vực chỉnh sửa tài liệu chính của Fileora.

#### Quản lý trang
- Thêm trang mới.
- Xóa trang.
- Nhân bản trang.
- Hiển thị danh sách thumbnail.
- Đánh số trang tự động.
- Chọn trang để chỉnh sửa.

#### Thêm hình ảnh
- Chọn một hoặc nhiều ảnh từ máy tính.
- Tự động tạo trang tương ứng.
- Giữ nguyên thứ tự ảnh được chọn.
- Hiển thị thumbnail bên ngoài.
- Hỗ trợ kéo thả ảnh.
- Dán ảnh bằng `CTRL + V`.

#### Nhập văn bản
- Tạo trang trắng.
- Nhập văn bản thủ công.
- Dán văn bản bằng `CTRL + V`.
- Chỉnh sửa văn bản trực tiếp.
- In đậm, in nghiêng, gạch chân.
- Thay đổi font chữ, cỡ chữ và màu sắc.
- Căn lề và điều chỉnh khoảng cách dòng.
- Hỗ trợ danh sách đánh số và gạch đầu dòng.

#### Sắp xếp trang
- Kéo thả thumbnail để thay đổi thứ tự.
- Hiệu ứng trực quan khi di chuyển.
- Đưa trang lên đầu hoặc xuống cuối.
- Cập nhật số thứ tự tự động.

#### Tùy chỉnh PDF
- Khổ giấy A4, A5, Letter.
- Hướng giấy dọc hoặc ngang.
- Điều chỉnh lề.
- Tùy chỉnh cách hiển thị hình ảnh.
- Xem trước trước khi xuất.

#### Xuất PDF
- Tổng hợp tất cả trang.
- Giữ đúng thứ tự.
- Giữ hình ảnh và nội dung văn bản.
- Giữ định dạng văn bản.
- Preview PDF.
- Tải xuống file PDF.

### 2.3. About – Giới thiệu

Thông tin người phát triển:

**Phan Văn Minh Đức**

Nghệ An, Việt Nam.

Giới thiệu về Fileora, mục đích xây dựng dự án và hướng dẫn sử dụng từng chức năng.

Có thêm mục FAQ để giải đáp các câu hỏi thường gặp.

---

## 3. Giao diện và trải nghiệm

Fileora sử dụng phong cách thiết kế kết hợp giữa:

- Apple-inspired UI.
- Glassmorphism.
- Neumorphism.
- 3D UI.
- Minimalism.

### Hệ thống Theme

Các giao diện dự kiến:

1. Light.
2. Dark.
3. Midnight.
4. Ocean.
5. Lavender.
6. Sakura.
7. Emerald.
8. Sunset.
9. Glass.

### Tùy chỉnh giao diện

- Accent Color.
- Border Radius.
- Animation.
- Transparency.
- Sound Effects.
- Light/Dark Mode.

Lưu thiết lập bằng `localStorage`.

### Animation

- Chuyển trang mượt mà.
- Hover effect.
- Button interaction.
- Drag & Drop animation.
- Loading animation.
- Toast notification.
- Modal transition.
- Glass effect.

Ưu tiên hiệu ứng tinh tế, không gây giật lag.

---

## 4. Công nghệ dự kiến

| Công nghệ | Vai trò |
|---|---|
| HTML5 | Cấu trúc website |
| CSS3 | Giao diện và animation |
| JavaScript | Xử lý chức năng |
| PDF.js | Hiển thị PDF |
| jsPDF / pdf-lib | Tạo PDF |
| SortableJS | Kéo thả sắp xếp |
| Mammoth.js | Đọc DOCX |
| SheetJS | Xử lý Excel |

Có thể tích hợp thêm thư viện phù hợp nếu cần.

Đối với những định dạng phức tạp cần chuyển đổi chính xác, có thể tích hợp backend sử dụng LibreOffice hoặc dịch vụ chuyển đổi chuyên dụng.

---

## 5. Cấu trúc dự án

Phiên bản ban đầu ưu tiên một file HTML duy nhất:

```text
Fileora/
│
└── index.html
```

Toàn bộ HTML, CSS và JavaScript được viết trong `index.html`.

Các thư viện bên ngoài có thể sử dụng CDN.

Không tạo thêm file CSS hoặc JavaScript riêng trong phiên bản này.

---

## 6. Nguyên tắc phát triển

1. Chức năng phải hoạt động thực tế.
2. Không tạo nút bấm giả.
3. Không giả lập kết quả chuyển đổi PDF.
4. Không làm mất dữ liệu khi chỉnh sửa.
5. Giữ đúng thứ tự trang khi xuất PDF.
6. Tối ưu hiệu suất khi xử lý nhiều ảnh.
7. Có thông báo lỗi rõ ràng.
8. Responsive trên máy tính và điện thoại.
9. Ưu tiên xử lý tài liệu ngay trên trình duyệt để bảo vệ quyền riêng tư.
10. Không tự ý gửi tài liệu lên máy chủ bên ngoài.

---

## 7. Lộ trình phát triển

- [ ] Xây dựng giao diện tổng thể.
- [ ] Xây dựng hệ thống điều hướng.
- [ ] Xây dựng Convert to PDF.
- [ ] Tích hợp preview PDF.
- [ ] Xây dựng Image & Document Studio.
- [ ] Thêm ảnh từ máy tính.
- [ ] Hỗ trợ CTRL + V hình ảnh.
- [ ] Hỗ trợ CTRL + V văn bản.
- [ ] Xây dựng trình soạn thảo văn bản.
- [ ] Xây dựng hệ thống kéo thả trang.
- [ ] Hoàn thiện chức năng xuất PDF.
- [ ] Xây dựng hệ thống Theme.
- [ ] Xây dựng trang About.
- [ ] Kiểm tra và tối ưu toàn bộ website.

---

## 8. Định hướng tương lai

Fileora có thể được phát triển thêm:

- Ghép nhiều file PDF.
- Tách PDF.
- Nén PDF.
- Xoay trang PDF.
- Đánh số trang.
- Thêm watermark.
- Chuyển PDF sang hình ảnh.
- Chuyển PDF sang Word.
- Chỉnh sửa PDF nâng cao.

Đây là những tính năng mở rộng, không bắt buộc trong phiên bản đầu tiên.

---

## 9. Credits

**Fileora – All-in-One PDF Studio**

Developed by **Phan Văn Minh Đức**

📍 Nghệ An, Việt Nam.

*Making document conversion simpler, smarter and more beautiful.*
