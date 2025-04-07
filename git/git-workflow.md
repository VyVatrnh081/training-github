# **Git Workflows**
## Định nghĩa cách các nhóm hoàn thành công việc bằng Git.

## **Centralized Workflow**:
- Sử dụng một nhánh duy nhất cho dự án.
- Các thành viên trong nhóm làm việc độc lập với các bản sao cục bộ của lịch sử dự án.
- Đơn giản nhưng không sử dụng các tính năng phân nhánh như yêu cầu kéo.

## **Feature Branch Workflow**:
- Công việc được thực hiện trong các nhánh tính năng và được hợp nhất thành một nhánh chạy lâu hơn.
- Khuyến khích cộng tác thông qua các yêu cầu kéo.

## **Forking Workflow**:
- Bao gồm nhiều kho lưu trữ từ xa, với một kho lưu trữ là nguồn gốc.
- Phổ biến trong các dự án nguồn mở, cho phép người dùng làm việc mà không cần quyền ghi vào kho lưu trữ gốc.

## **GitFlow Workflow**:
- Hỗ trợ các bản phát hành liên tục với nhiều nhánh.
- Bao gồm các nhánh chạy lâu (master và development) và các nhánh tồn tại trong thời gian ngắn cho các tính năng và bản sửa lỗi nhanh.
- Nhấn mạnh các hoạt động hợp nhất để đảm bảo chất lượng và thử nghiệm.
