# Nhật ký sử dụng AI – Portfolio v7

## Vấn đề ban đầu

- File `AI_log.md` ban đầu ghi nhận lỗi không hiển thị trang, lỗi không tìm thấy đường dẫn trong terminal và lỗi không hiển thị ảnh.
- Qua kiểm tra cấu trúc thực tế, dự án có đủ HTML, CSS và bốn ảnh trong `assets/`. Nội dung các file HTML/Markdown được đọc không đúng mã hóa trong môi trường kiểm tra, vì vậy đã chuẩn hóa lại nội dung bằng UTF-8.
- Đoạn mô tả Apollo EVO trong `index.html` bị dính câu sau dấu chấm.

## Nhận định ban đầu của sinh viên

Nội dung nhận định cụ thể ngoài ba vấn đề được ghi trong file log cũ: **sinh viên cần bổ sung nếu có**.

## Công cụ AI đã sử dụng

- Trợ lý AI trong VS Code để kiểm tra cấu trúc thư mục, đọc file, chỉnh sửa file và kiểm tra tĩnh.
- PowerShell dùng để liệt kê file và kiểm tra trạng thái Git trong quá trình làm việc.

## Nội dung yêu cầu AI hỗ trợ

- Hoàn thiện Portfolio v7 theo yêu cầu bài đánh giá A2.2.
- Kiểm tra HTML5, CSS3, tài nguyên ảnh, biểu mẫu liên hệ và tài liệu dự án.

## Gợi ý AI đưa ra

- Chuẩn hóa tên `AI_LOG.md` theo cấu trúc yêu cầu.
- Sửa nội dung hiển thị tiếng Việt, khoảng cách câu Apollo EVO, alt ảnh và các ràng buộc của form.
- Bổ sung xử lý nội dung dài để giảm nguy cơ tràn ngang trên thiết bị nhỏ.

## Những thay đổi đã chấp nhận

- Cập nhật `index.html` và `ket-qua.html` bằng HTML5 hợp lệ, liên kết đúng đến CSS/ảnh và có nội dung tiếng Việt đúng mã hóa.
- Sửa mô tả Apollo EVO, alt ảnh, điều hướng, form và nút quay lại.
- Cập nhật CSS để giữ giao diện hiện tại, hỗ trợ focus bằng bàn phím, ảnh không méo và nội dung dài không gây tràn ngang.
- Tạo README, release notes và checklist.

## Những thay đổi đã từ chối

- Không thêm framework, JavaScript, thông tin cá nhân mới hoặc hiệu ứng thiết kế mới.
- Không tự nhận đã tạo commit, push repository hoặc triển khai GitHub Pages.

## Kết quả kiểm tra sau khi sửa

- Đã kiểm tra tĩnh cấu trúc file và các đường dẫn tương đối trong HTML: **ĐÃ KIỂM TRA**.
- Đã kiểm tra sự tồn tại của bốn ảnh yêu cầu: **ĐÃ KIỂM TRA**.
- Đã kiểm tra thuộc tính form `required`, `minlength`, `maxlength`, `type="email"` và `action="ket-qua.html"`: **ĐÃ KIỂM TRA**.
- Kiểm tra trực tiếp trên trình duyệt, kiểm tra responsive bằng thiết bị thực, GitHub Pages và ảnh chụp kiểm chứng: **CHƯA KIỂM TRA** – sinh viên cần thực hiện và bổ sung kết quả.
