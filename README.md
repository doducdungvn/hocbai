# 📚 Trợ Lý Học Tập — Bản Đặc Quyền Xuân Lâm V21.0

Ứng dụng web luyện tập và kiểm tra kiến thức trực tuyến toàn diện dành cho học sinh từ **Lớp 1 đến Lớp 12**, bám sát theo **Chương trình Giáo dục phổ thông (GDPT 2018) của Bộ Giáo dục và Đào tạo**.

---

## 🌟 Tính Năng Nổi Bật

### 1. 📱 Thiết Kế Đa Nền Tảng (Responsive)
- **Tối ưu toàn màn hình (Full Screen):** Không bị giới hạn khung viền, tối đa hóa không gian đọc và làm bài.
- **Giao diện Điện thoại (Mobile-First):**
  - Mở web là thấy ngay bảng chọn Lớp, Môn và Dạng bài để bắt đầu làm bài nhanh chóng.
  - Khi bắt đầu thi, bảng thiết lập tự đóng lại để nhường trọn màn hình cho câu hỏi.
  - Bảng thống kê **Điểm số**, **Số câu**, **Thời gian làm bài** và thanh tiến trình được ghim trực quan ngay phía trên câu hỏi (giữa thanh Topbar và nội dung bài thi).
- **Giao diện Máy tính (Desktop):** Bố cục 2 cột chuyên nghiệp với Sidebar điều khiển bên trái và màn hình câu hỏi lớn bên phải.

### 2. 🎯 Phân Loại 2 Dạng Bài Tập Riêng Biệt
Mỗi môn học ở từng khối lớp đều được chia làm 2 hình thức rèn luyện:
- **Cơ bản (Trắc nghiệm - MCQ):** Giao diện 4 lựa chọn (A, B, C, D) với kích thước nút bấm lớn. Học sinh chỉ cần nhấp chọn đáp án, hệ thống lập tức chấm điểm và làm nổi bật màu xanh (nếu đúng) hoặc đỏ (nếu sai).
- **Nâng cao (Tự luận):** Ô nhập đáp án thông minh, khuyến khích học sinh tự tính toán, ghi nhớ từ vựng hoặc phân tích đáp án chi tiết.

### 3. 📖 Nội Dung Môn Học Đầy Đủ (Lớp 1 – 12)
Hệ thống ngân hàng câu hỏi phong phú bao phủ đầy đủ các môn học theo chuẩn Bộ GD&ĐT:
- 🧮 **Toán học** (Lớp 1 – 12)
- 🇻🇳 **Tiếng Việt / Ngữ Văn** (Lớp 1 – 12)
- 🇬🇧 **Tiếng Anh** (Lớp 1 – 12)
- 🔬 **Khoa học / Khoa học tự nhiên** (Lớp 1 – 9)
- ⚡ **Vật lý** (Lớp 10 – 12)
- 🧪 **Hóa học** (Lớp 10 – 12)
- 🌿 **Sinh học** (Lớp 10 – 12)
- 📜 **Lịch sử & Địa lý** (Lớp 4 – 5)
- 📜 **Lịch sử** (Lớp 6 – 12)
- 🌍 **Địa lý** (Lớp 6 – 12)

### 4. 💡 Gợi Ý Thông Minh
- Phần gợi ý kiến thức tự động hiển thị **ngay cạnh nút "Câu tiếp theo"** khi học sinh trả lời chưa đúng hoặc bấm "Bỏ qua".
- Tự động ẩn đi khi chuyển sang câu hỏi mới hoặc khi trả lời đúng để tránh gây rối mắt.

### 5. 💾 Lưu Phiên Tự Động (Session Persistence)
- Tiến độ bài thi (tên học sinh, câu hỏi hiện tại, điểm số, thời gian) được lưu liên tục vào `localStorage`.
- Nếu vô tình tắt trình duyệt, tải lại trang hoặc mất mạng, khi vào lại trang sẽ có hộp thoại hỏi: **Tiếp tục phiên cũ** hay **Làm bài mới**.

### 6. 🤖 Trợ Lý Trí Tuệ Nhân Tạo (Gemini AI)
- Tích hợp Google Gemini API để hỗ trợ tự động mở rộng và sinh câu hỏi mới phong phú theo đúng môn và khối lớp học yêu cầu.

### 7. 🏆 Báo Cáo Kết Quả & Chia Sẻ Nhanh
- **Màn hình khen thưởng (Reward Screen):** Thống kê chi tiết điểm thi, số câu đúng/tổng, thời gian hoàn thành, xếp loại học lực kèm hiệu ứng pháo hoa rực rỡ khi điểm số cao.
- **📷 Chụp gửi Zalo:** Tự động vẽ Bảng Vàng thành ảnh và copy vào bộ nhớ tạm (Clipboard), phụ huynh/học sinh chỉ cần bấm `Ctrl + V` vào Zalo để gửi ngay.
- **⬇️ Tải Bảng Vàng:** Tải ảnh Bảng Vàng kết quả thi (.PNG) độ phân giải cao về máy để lưu giữ kỷ niệm.

### 8. 📊 Bảng Quản Trị Admin & Đồng Bộ Google Sheets
- Đăng nhập Admin bảo mật bằng mã PIN (không hiển thị mật khẩu mặc định).
- Tự động ghi nhận và phân loại 3 trạng thái rõ ràng:
  - **✓ Xong:** Khi hoàn thành toàn bộ 50 câu hỏi.
  - **❌ Bỏ dở:** Khi học sinh bấm Làm mới, thoát bài thi giữa chừng hoặc tắt trình duyệt quá thời gian quy định (thay vì bị treo vĩnh viễn ở trạng thái "Đang thi").
  - **⚡ Đang thi:** Đang trong quá trình làm bài thi trực tiếp.
- Bộ lọc tìm kiếm học sinh và cập nhật dữ liệu trực tiếp trong trang quản trị.

---

## 🚀 Hướng Dẫn Cài Đặt & Triển Khai

Ứng dụng được viết theo dạng **Single Page Application (SPA)** thuần túy bằng HTML5, Vanilla JavaScript và Tailwind CSS CDN. Không yêu cầu cài đặt môi trường Node.js hay biên dịch mã nguồn.

### Cách 1: Chạy trên Web Server IIS (Windows)
1. Đặt file `hocbai.html` vào thư mục gốc của IIS:
   ```text
   C:\inetpub\wwwroot\hocbai.html
   ```
2. Mở trình duyệt và truy cập:
   ```text
   http://localhost/hocbai.html
   ```
   *(hoặc địa chỉ IP mạng nội bộ của máy chủ)*.

### Cách 2: Chạy trực tiếp bằng bất kỳ Web Server nào
- **Live Server (VS Code):** Nhấp chuột phải vào `hocbai.html` chọn **Open with Live Server**.
- **Python HTTP Server:** Mở terminal tại thư mục chứa file và chạy:
  ```bash
  python -m http.server 8080
  ```
- **Nginx / Apache:** Đặt file vào thư mục `html` hoặc `htdocs`.

---

## ⚙️ Cấu Hình Hệ Thống

Các thông số mặc định có thể tùy chỉnh trực tiếp trong file mã nguồn hoặc qua giao diện cài đặt:

| Tham số | Vị trí | Mô tả |
|---|---|---|
| `GEMINI_KEY` | Trong file JS | Khóa API của Google Gemini để sinh câu hỏi |
| `SHEETS_URL` | Trong file JS / Admin | Đường dẫn Google Apps Script Web App để nhận kết quả thi |
| `Mã PIN Admin` | Mặc định: `admin123` | Mã mở Bảng Quản Trị (có thể đổi trực tiếp trong modal Admin) |
| `Cỡ chữ` | Nút ⚙️ Cấu hình | Chọn cỡ chữ: Nhỏ, Vừa, Lớn, Rất lớn phù hợp thị lực |

---

## 📋 Hướng Dẫn Sử Dụng Cho Học Sinh

1. **Bước 1:** Chọn **Khối lớp** (Lớp 1 đến 12).
2. **Bước 2:** Chọn **Môn học** cần ôn luyện.
3. **Bước 3:** Chọn **Dạng bài**: *Cơ bản (Trắc nghiệm)* hoặc *Nâng cao (Tự luận)*.
4. **Bước 4:** Nhập họ tên học sinh vào ô.
5. **Bước 5:** Bấm **🚀 Bắt đầu làm bài**.
6. **Bước 6:** Trả lời các câu hỏi:
   - Với câu trắc nghiệm: Nhấp vào đáp án A, B, C hoặc D.
   - Với câu tự luận: Gõ câu trả lời vào ô và bấm **✅ Kiểm tra** (hoặc phím Enter).
   - Nếu câu khó quá có thể bấm **⏭️ Bỏ qua** để xem gợi ý.
7. **Bước 7:** Hoàn thành 50 câu hỏi, hệ thống sẽ tính điểm và hiển thị Bảng Vàng vinh danh!

---

## 📄 Bản Quyền & Phát Triển
- **Phiên bản:** Xuân Lâm V21.0
- **Năm cập nhật:** 2026
- Phát triển phục vụ mục đích học tập, rèn luyện kỹ năng và nâng cao kiến thức cho học sinh.
