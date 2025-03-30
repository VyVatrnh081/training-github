# training-github
- git and github
- những khái niệm cơ bản
# sự khác nhau giữa git và github
![Untitled](https://github.com/user-attachments/assets/4f33f5d3-ad06-406d-bd87-655a86376881)

- Git là nền tảng, còn GitHub là dịch vụ cung cấp giao diện và công cụ giúp sử dụng Git dễ dàng hơn.
- Có thể sử dụng Git mà không cần GitHub, nhưng GitHub thì cần Git để hoạt động.
- GitHub giúp làm việc nhóm hiệu quả hơn nhờ các tính năng như pull request, issue tracking, code review.
- Ngoài GitHub, còn có các dịch vụ khác cũng dựa trên Git như GitLab, Bitbucket, Azure DevOps.
# repository
Nơi phân loại, lưu trữ các file cấu hình, các script, các bản nháp, ... và nó được lưu ở máy trạm và ở GitHub Server.
- 2 loại:
  + Remote repository: Là repository để chia sẻ giữa nhiều người và bố trí trên server chuyên dụng.
  + Local repository: Là repository bố trí trên máy tính, dành cho một người dùng sử dụng.
- 3 trạng thái của Repository:
  + Working directory
  + Stagging area
  + Git 
## 1. Branch
- Một nhánh là một phiên bản song song của mã nguồn trong kho lưu trữ (Repository).
- Cho phép làm việc trên các tính năng hoặc sửa lỗi mà không ảnh hưởng đến nhánh chính (main/ master).
- Khi hoàn thành, có thể hợp nhất (Merge) nhánh vào nhánh chính.
## 2. Clone
- Tải xuống 1 bản sao đầy đủ của Git Repository từ GitHub về máy tính cục bộ (local computer/ owner computer).
- Bao gồm toàn bộ lịch sử thay đổi (commit history) và tất cả các tập tin trong repo.
- git cmd: **git clone <repo-url>**
## 3. Fork 
- Tạo 1 bản sao của 1 repository về GitHub Personal Accoount.
- Cho phép thay đổi source code mà không ảnh hưởng tới Original Repository.
- Hữu ích khi muốn đóng góp vào 1 dự án mã nguồn mở (Open-Source Project).
## 4. Merge
- Quá trình kết hợp thay đổi từ một nhánh vào một nhánh khác.
- git cmd: **git merge <branch-name>**
## 5. Pull Request 
- Yêu cầu để hợp nhất thay đổi từ một nhánh vào một nhánh khác trên GitHub.
- Khi tạo một pull request, người khác có thể xem xét, nhận xét và phê duyệt trước khi thay đổi được hợp nhất.
- Đặc biệt quan trọng khi làm việc nhóm.
## 6. Remote
- Là kho lưu trữ Git được lưu trên GitHub hoặc một máy chủ từ xa thay vì trên máy tính cá nhân.
- Cho phép nhiều người cùng làm việc trên cùng một dự án.
- git cmd: **git remote -v** : xem danh sách remote repositories.
## 7. Upstream
- Upstream đề cập đến repository gốc đã được fork hoặc clone.
- Khi fork một repository, upstream repository là nguồn gốc có thể lấy (fetch) các thay đổi mới nhất.
- git cmd: **git remote add upstream <original-repo-url>**.
