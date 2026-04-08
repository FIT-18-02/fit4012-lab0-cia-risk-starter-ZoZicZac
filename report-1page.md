# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu người dùng (tài khoản, mật khẩu, thông tin cá nhân)
- Hệ thống máy chủ và cơ sở dữ liệu

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Kẻ tấn công hoặc người dùng nội bộ chỉnh sửa dữ liệu trái phép
- Vulnerability: Phân quyền không rõ ràng, thiếu kiểm tra đầu vào, không có cơ chế kiểm tra tính toàn vẹn dữ liệu
- Mitigation: Áp dụng phân quyền chặt chẽ, kiểm tra dữ liệu đầu vào, sử dụng logging và cơ chế xác thực/kiểm tra toàn vẹn

### 4. Kết luận ngắn
Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng trong việc phân tích các sự cố an toàn thông tin. Em biết cách xác định tài sản quan trọng và liên hệ từng sự cố với các yếu tố bảo mật tương ứng. Phần khó nhất là phân biệt giữa các yếu tố trong CIA khi tình huống không rõ ràng. Bài lab giúp em rèn luyện tư duy phân tích threat, vulnerability và mitigation một cách logic. Khi phân tích sự cố, cần đọc kỹ bối cảnh để xác định đúng bản chất vấn đề.