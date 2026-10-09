# DevOps Hackathon - Đề 022: Quản lý sản phẩm (Shop)

## 1. Thông tin sinh viên
|Họ và tên|Mã sinh viên|Lớp|Tài khoản Linux|GitHub|Cổng Nginx|
|Phan Trung Kiên|N24DTCN048|HCM-K24-CNTT1|phantrungkien-k24cntt1|https://github.com/KienPhan1109/devops-hackathon-de002-phantrungkien.git|8081|

## 2. Môi trường triển khai
- Hệ điều hành: Linux
- Phiên bản Nginx: nginx/1.24.0 (Ubuntu)
- Phiên bản Git: 2.43.0

## 3. Cấu trúc dự án
nginx
    |
    |-phantrungkien-k24cntt1.conf
screenshots
    |
    |-01-user.png
    |-02-nginx.png
    |-03-ufw.png
    |-05-git-log.png
src
    |
    |-index.html
.gitignore
README.md

## 4. Cấu hình Nginx

## 5. Tường lửa UFW
|To|Action|From|
|22/tcp|ALLOW IN|Anywhere|
|8081:8083/tcp|ALLOW IN|Anywhere|
|8080/tcp|ALLOW IN|Anywhere|
|22/tcp (v6)|ALLOW IN|Anywhere (v6)|
|8081:8083/tcp (v6)|ALLOW IN|Anywhere (v6)|
|8080/tcp (v6)|ALLOW IN|Anywhere (v6)|

