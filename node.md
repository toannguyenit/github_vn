# Terms

Repository (Repo) // Một cái kho, thư mục chứa dự án
Branch // Nhánh code
Conflict // Xung đột
Local // Máy tính của chúng ta  
Remote // Github
url // https://github.com/toannguyenit/github_vn.git

# Commands

# git init // Khởi tạo git, dự án có thể chạy git

# git status // Cho thấy dự án có thay đổi gì

# git add // Chuẩn bị lưu lại thời điểm hiện tại của dự án

    $ git add {file name}   // Chuẩn bị Lưu lại một file
    $ git add .             // Chuẩn bị Lưu lại tất cả những file có sự thay đổi

# git reset // Clear các thời điểm lưu lại của dự án

# git commit // Ghi chú, đặt tên cho thời điểm lưu

    $ git commit -m '{commit content}'

# git log // Xem lại các thời điểm đã lưu

    $ git log
    $ git log --oneline     // Xem lại thời điểm đã lưu một cách gọn hơn

# git checkout

    $ git checkout {id commit}      // chọn thời điểm đã lưu của commit
    $ git checkout {branch name}    // chọn thời điểm hiện tại của branch
    $ git checkout -b {branch name} // Khởi tạo một branch mới

# git branch

    $ git branch                    // Xem danh sách branch
    $ git branch -d {branch name}   // Xóa một branch

# git merge

    $ git merge {branch name}       // Hợp nhất dữ liệu với một branch nào đó

# git push // Đẩy dự án từ local lên remote(GitHub)

    $ git push {url} {branch name}      // Đẩy dữ liệu lên remote
    $ git push -u {url} {branch name}   // Đẩy một branch dưới local lên remote

    $ git remote add {remote name} {url}       // Gán tên một url thành origin (Có thể đổi thành tên khác)

    $ git push origin {branch name}      // Đẩy dữ liệu lên remote
    $ git push -u origin {branch name}   // Đẩy một branch dưới local lên remote

    $ git fetch origin                   // Một lệnh trong Git được sử dụng để tải về các thay đổi mới nhất từ nhánh gốc (origin) của repository từ xa mà bạn đã được liên kết

    $ git checkout -b {branch name} origin/{branch name}

    $ git checkout -b stagin origin/stagin // Một lệnh dùng để kéo về một branch từ remote (Ở đây branch đó tên la stagin)

# git pull
    $ git pull                          // Phải tạo một git pull request sau đó sử dụng cách này để pull