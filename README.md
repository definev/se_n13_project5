# se_n13_project5: Tidmid - Phần mềm Ghi chú và Chatbot với Trí tuệ Nhân tạo
Tidmid là một dự án phần mềm được phát triển bởi nhóm se_n13_project5. Dự án nhằm cung cấp cho người dùng một ứng dụng ghi chú tiện lợi và một chatbot được trang bị công nghệ Trí tuệ Nhân tạo.

## Cấu trúc Dự án
Dự án được chia thành các thư mục sau:

`mobile_app`: Thư mục này chứa ứng dụng di động, được xây dựng bằng Flutter. Người dùng có thể ghi chú và tương tác với chatbot thông qua ứng dụng này.

`server`: Thư mục này chứa máy chủ backend, được xây dựng bằng FastAPI. Máy chủ này liên lạc với ứng dụng di động và xử lý các yêu cầu liên quan đến ghi chú và tương tác chatbot. Cơ sở dữ liệu được sử dụng là MySQL.

`server/deployment`: Thư mục này chứa các tệp cấu hình Docker cần thiết để triển khai ứng dụng.

## Bắt đầu
Để chạy ứng dụng, bạn cần phải cài đặt Docker trên máy tính của mình. Sau khi cài đặt Docker, bạn có thể làm theo các bước sau:

1. Sao chép kho lưu trữ này vào máy tính của bạn.
2. Di chuyển đến thư mục server/deployment.
3. Tạo một thư mục có tên là env trong server/deployment.
4. Tạo 3 tệp tin trong thư mục env: .app.env, .db.env, .openai.env. Những tệp tin này sẽ chứa các biến môi trường cần thiết cho ứng dụng. Tham khảo các tệp mẫu .env.sample tương ứng trong cùng thư mục để biết các biến cần thiết.
5. Chạy lệnh sau để bắt đầu ứng dụng: docker-compose up.
6. Sau khi ứng dụng đã chạy, bạn có thể truy cập vào ứng dụng di động tại địa chỉ http://localhost:8080.

## Đóng góp
Chúng tôi hoan nghênh mọi đóng góp cho dự án này. Nếu bạn quan tâm đến việc đóng góp, hãy tạo một yêu cầu kéo và chúng tôi sẽ xem xét nó sớm nhất có thể.

## Giấy phép
Dự án này được phân phối theo giấy phép MIT. Xem tệp LICENSE để biết chi tiết.
