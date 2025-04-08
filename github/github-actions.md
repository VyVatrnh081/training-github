# Sự khác biệt giữa CI/CD

![image](https://github.com/user-attachments/assets/23c82d28-9739-4fdd-86eb-6970a592b780)

## CI/CD là 2 quá trình riêng biệt
### CI - Continuous Intergration: tích hợp liên tục code với nhánh main/master/trunk của hệ thống.
- Khi nhiều người cùng làm việc trên cùng một dự án, mỗi người sẽ làm ở nhánh riêng.
- Sau khi hoàn thành một phần, họ sẽ merge vào nhánh chính.
- CI đảm bảo rằng việc merge diễn ra thường xuyên để tránh lỗi và xung đột code.
- Trong quá trình merge, hệ thống sẽ tự động build và test để phát hiện lỗi sớm
### CD - Continuous Delivery: đóng gói và triển khai code đã tích hợp vào 1 môi trường trung gian (môi trường kiểm thử).
- development server
- test/staging server
- pre-production server
### Continuous Deployment
- Tự động triển khai vào môi trường production (môi trường chính) mà không cần con người can thiệp.
- Thay đổi code hợp lệ -> auto test -> pass -> triển khai cho người dùng

![image](https://github.com/user-attachments/assets/f0262739-8cda-4a69-bb24-b5e806b03f8d)

## Lợi ích
1. Phản hồi nhanh chóng với thay đổi code

Code được kiểm thử và build ngay lập tức → dễ thấy lỗi và sửa nhanh.

2. Giảm rủi ro tích hợp

Merge code thường xuyên → tránh tình trạng “code của tôi và code của bạn đụng nhau”.

3. Nâng cao chất lượng code

Luôn có kiểm thử và review tự động → chất lượng cải thiện theo thời gian.

4. Luôn đảm bảo nhánh chính hoạt động tốt

Luôn giữ cho nhánh main/master có thể triển khai được.

5. Rút ngắn thời gian triển khai

Tự động hóa → không tốn công sức thủ công → triển khai nhanh hơn, ít lỗi hơn.
