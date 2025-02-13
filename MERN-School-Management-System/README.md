# TOPIC: MERN School Management System 

Website Quản lý học tập và giảng dạy tại trường THPT này là một ứng dụng web được xây dựng bằng công nghệ MERN (MongoDB, Express.js, React.js, Node.js). Website này nhằm mục đích đơn giản hóa việc quản lý trường học, tổ chức lớp học và thúc đẩy giao tiếp giữa học sinh, giáo viên và quản trị viên.

**Các Chức Năng**
- Phân Quyền Người Dùng: Hệ thống hỗ trợ ba loại người dùng gồm Quản trị viên (Admin), Giáo viên và Học sinh. Mỗi loại có các chức năng và mức truy cập riêng.

- Bảng Điều Khiển Quản Trị: Quản trị viên có thể thêm học sinh và giáo viên mới, tạo lớp học và môn học, quản lý tài khoản người dùng và giám sát các cài đặt của hệ thống.

- Theo Dõi Điểm Danh: Giáo viên có thể dễ dàng điểm danh cho các lớp của mình, đánh dấu học sinh có mặt hoặc vắng mặt và tạo báo cáo điểm danh.

- Đánh Giá Hiệu Suất Học Tập: Giáo viên có thể đánh giá hiệu suất học tập của học sinh bằng cách cho điểm và phản hồi. Học sinh có thể xem điểm số và theo dõi tiến độ của mình qua thời gian.

- Trực Quan Hóa Dữ Liệu: Học sinh có thể xem dữ liệu hiệu suất của mình qua các biểu đồ và bảng tương tác, giúp họ dễ dàng nắm bắt tình hình học tập.

**Công Nghệ Sử Dụng**
- Frontend: React.js, Material UI, Redux
- Backend: Node.js, Express.js
- Cơ sở dữ liệu: MongoDB

**Cài Đặt Và Chạy Code**

***Terminal 1: Cài đặt Backend***
```sh
cd backend
```
- Cấu hình môi trường bằng cách truy cập .env
```sh
MONGO_URI=mongodb://localhost:27017/<ten-database>
```
hoặc 
```sh
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/<database-name>?retryWrites=true&w=majority
```
- Chạy chương trình
```sh
npm install
npm start
```
***Terminal 2: Cài đặt Frontend***
```sh
cd frontend
npm install
npm start
```

Truy cập vào localhost:3000 trên trình duyệt để chạy Frontend và API Backend sẽ chạy tại địa chỉ localhost:5000