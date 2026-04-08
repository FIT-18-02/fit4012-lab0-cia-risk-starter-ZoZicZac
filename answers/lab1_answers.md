# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Vũ Phương

**MSSV:** 1871020459

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu người dùng (thông tin cá nhân, tài khoản, mật khẩu)
- Asset 2: Hệ thống máy chủ (server, database)
- Asset 3 (nếu có): Ứng dụng/web service cung cấp cho người dùng

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality (Bảo mật)
(Ví dụ: lộ dữ liệu người dùng)
- Sự cố B ->Integrity (Toàn vẹn)
(Ví dụ: dữ liệu bị sửa trái phép)
- Sự cố C ->Availability (Sẵn sàng)
(Ví dụ: hệ thống bị sập, không truy cập được)

---

## 3. Phân tích sự cố B
- Threat:Hacker hoặc người dùng nội bộ cố ý thay đổi dữ liệu (ví dụ sửa điểm, sửa thông tin tài khoản)
- Vulnerability:
Không kiểm tra đầu vào (input validation kém)
Phân quyền không rõ ràng
Không có cơ chế kiểm tra tính toàn vẹn dữ liệu
- Mitigation:
Áp dụng kiểm soát truy cập (Access Control)
Sử dụng hashing / checksum để kiểm tra dữ liệu
Ghi log và audit hệ thống
Validate dữ liệu đầu vào chặt chẽ
---

## 4. Reflection
Viết 5-7 dòng.

Qua bài tập này, em hiểu rõ hơn về mô hình CIA trong an toàn thông tin, bao gồm bảo mật, toàn vẹn và tính sẵn sàng của hệ thống. Việc phân tích các sự cố giúp em nhận ra rằng mỗi vấn đề bảo mật đều liên quan đến một hoặc nhiều yếu tố trong CIA. Ngoài ra, em cũng học được cách xác định mối đe dọa, điểm yếu và biện pháp khắc phục. Điều này rất quan trọng trong việc thiết kế hệ thống an toàn. Trong tương lai, em sẽ chú ý hơn đến việc bảo vệ dữ liệu và kiểm soát truy cập khi phát triển phần mềm.

---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-C-B-I-C-A}

