# git .ignore
.gitignore là một tệp trong Git dùng để chỉ định các tệp và thư mục mà bạn muốn Git bỏ qua, không theo dõi hoặc không đưa vào hệ thống quản lý phiên bản.
# Công dụng
- Tránh đưa các tệp không cần thiết (như tệp tạm, log, thư viện bên ngoài, thông tin nhạy cảm, v.v.) vào Git.
- Giữ cho repo sạch sẽ, chỉ chứa các tệp thực sự quan trọng cho dự án.
- Tăng tốc độ làm việc vì Git không phải theo dõi các tệp không liên quan.
# gitignore file Patterns and Format (.gitignore)
- Dòng trống: Một dòng trống không tham chiếu đến bất kỳ tên tệp nào, vì vậy có thể dùng để tách biệt các tên tệp, giúp dễ đọc hơn.
- #: Một dòng bắt đầu bằng ký tự # là một dòng chú thích. Tuy nhiên, nếu # được dùng như một mẫu ký tự (pattern), cần thêm dấu gạch chéo ngược (\) trước # để tránh bị hiểu nhầm là chú thích.
- /: Được dùng như một dấu phân cách thư mục, giúp chỉ định thư mục, ví dụ: webdev/.
- *.tên_định_dạng: Ví dụ *.txt và *.log sẽ khớp với tất cả các tệp có phần mở rộng .txt và .log.
- **/tên_bất_kỳ: Dùng để khớp với bất kỳ tệp hoặc thư mục nào có tên là tên_bất_kỳ, ở bất kỳ cấp thư mục nào.
- tên_bất_kỳ/: Dùng để khớp với tất cả các tệp bên trong thư mục có tên tên_bất_kỳ. Ví dụ, webdev/ sẽ khớp với tất cả các tệp bên trong thư mục webdev
# Quy tắc trong .gitignore
- Các tệp được liệt kê trong .gitignore phải tuân theo một mẫu quy tắc cụ thể.
- Git sẽ đọc tệp .gitignore từ trên xuống dưới, nên thứ tự các dòng có thể ảnh hưởng đến cách Git xử lý.
- .gitignore hỗ trợ phủ định (negation) bằng cách sử dụng ! làm tiền tố (prefix).
- *.log → Bỏ qua tất cả các tệp có phần mở rộng .log.
- build/ → Bỏ qua toàn bộ thư mục build.
- Có thể thêm chú thích trong .gitignore bằng cách sử dụng ký tự #.
# Nguồn tham khảo thêm
- [what is git .ignore](https://www.geeksforgeeks.org/what-is-git-ignore-and-how-to-use-it/)  (geeksforgeeks)
- [gitignore](https://git-scm.com/docs/gitignore) (gitdocs)
