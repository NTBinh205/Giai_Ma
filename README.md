Game “Giải mã kho báu”

Mô tả
Trò chơi giáo dục kết hợp yếu tố phiêu lưu và an toàn thông tin, giúp người chơi hiểu và thực hành giải mã thông điệp mã hóa để tìm ra kho báu bí ẩn.

1. Giới thiệu bài toán

Mục tiêu: Xây dựng một game tương tác, sử dụng các thuật toán mã hóa (Caesar, Vigenère, RSA, AES) để tạo chuỗi câu đố.

Ý nghĩa: Rèn luyện tư duy logic, kiến thức an ninh mạng và kỹ năng giải mã.

Cốt truyện: Người chơi vào vai thám tử nhận loạt thông điệp mã hóa từ tổ chức bí mật, lần lượt giải mã để tìm manh mối và cuối cùng khám phá kho báu.

2. Kỹ thuật & Công nghệ

Ngôn ngữ lập trình: Python (Flask/FastAPI) hoặc JavaScript (Node.js + React)

Backend: Flask/Django (Python) hoặc Express.js (Node.js)

Frontend: React hoặc Vue.js; Tuỳ chọn Desktop: Tkinter/PyQt

Database: SQLite hoặc MongoDB (lưu tiến trình, điểm số)

Thuật toán mã hóa:

Caesar Cipher

Vigenère Cipher

RSA (Khóa công khai/khóa riêng)

AES (mã hóa đối xứng)

Công cụ: Git/GitHub, VS Code, Postman (API test)

3. Các chức năng chính

Chọn cấp độ chơi

Level 1 → Caesar Cipher

Level 2 → Vigenère Cipher

Level 3 → RSA

Level 4 → AES

Giải mã thông điệp

Giao diện nhập thông điệp + tham số giải mã (độ dịch, từ khóa, khóa riêng/bí mật)

Nút “Giải mã” và hiển thị kết quả

Phản hồi & Gợi ý

Thông báo thành công/thất bại

Tùy chọn xem gợi ý hoặc đáp án tham khảo

Điểm số & Tiến trình

Tính điểm khi giải đúng

Lưu cấp độ và tổng điểm

Hỗ trợ người chơi

Hướng dẫn thuật toán (modal Help)

Reset cấp độ và điểm

4. Giao diện & Hoạt động

Màn hình chính

Logo & tiêu đề game

Nút “Bắt đầu”

Thanh thông tin: cấp độ hiện tại, điểm số

Màn hình giải mã

Hiển thị thông điệp đã mã hóa

Form nhập tham số:

Level 1: độ dịch (số nguyên)

Level 2: từ khóa (chuỗi)

Level 3: khóa riêng (dãy số lớn)

Level 4: khóa bí mật (chuỗi nhị phân)

Nút “Giải mã”

Màn hình phản hồi

Hiển thị kết quả: thông điệp giải mã và manh mối tiếp theo

Thông báo: Thành công/Thất bại + nút xem gợi ý

Nút “Tiếp tục” lên cấp độ kế tiếp

Màn hình kết thúc

Chúc mừng khi hoàn thành AES

Tổng kết: điểm số, thời gian chơi

Nút “Chơi lại” hoặc “Thoát”
