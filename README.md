# Báo cáo kiểm thử API

## Ngày kiểm thử: 19/06/2025

## Giới thiệu
Postman là công cụ API được sử dụng để gửi, tạo, kiểm thử và quản lí các yêu cầu. Postman có các chức năng:
- Tạo yêu cầu HTTP
- Kiểm thử tự động
- Quản lí biến môi trường và biến toàn cục

## Những thành phần chính
- Settings: cung cấp tùy chọn cài đặt chung về trải nghiệm sử dụng và hiệu suất ứng dụng
- Collections: cung cấp cách thức lưu trữ, sắp xếp và chia sẻ các yêu cầu API dễ dàng.  
Các thành phần Collections trong postman:
    Lưu trữ yêu cầu: cho phép tạo và lưu trữ các yêu cầu HTTP gồm các phương thức GET POST PUT DELETE và các yêu cầu khác.  
  Sắp xếp và quản lý: Tổ chức các yêu cầu theo nhóm cụ thể, giúp dễ dàng quản lý, tìm kiếm và thực hiện các thao tác nhóm trên chúng.  
  Chia sẻ và sử dụng chung: chia sẻ collection với đồng nghiệp hoặc cộng đồng qua các liên kết, hoặc sử dụng collection có sẵn từ cộng đồng.  
  Kiểm thử tự động: hỗ trợ việc tạo và quản lý các bộ kiểm thử tự động, cho phép kiểm tra tính đúng đắn và hiệu suất của API một cách tự động.  
- API content: "API content" thường đề cập đến dữ liệu cụ thể mà bạn gửi hoặc nhận từ các APIs đang tương tác. Người dùng cần lưu ý các chức năng trong thành phần này như sau.  
  Headers (Đầu mục): Thông tin tiêu đề gửi đi hoặc nhận về, bao gồm thông tin như kiểu ngôn ngữ (content-type), định dạng (JSON, XML) và các thông tin xác thực.  
  Body (Nội dung): Dữ liệu cụ thể được gửi đi hoặc nhận về từ API, có thể chứa thông tin tương tác như thông tin đăng ký, thông tin sản phẩm hoặc bất kỳ dữ liệu nào khác mà API yêu cầu hoặc gửi lại.  
  Response (Phản hồi): Thông tin phản hồi từ API sau khi bạn gửi yêu cầu, bao gồm trạng thái HTTP (200, 404, v.v.), dữ liệu phản hồi và thông tin khác như thời gian phản hồi.
## Thực hành các chức năng postman
- Yêu cầu GET Lấy dữ liệu từ server.
![image](https://github.com/user-attachments/assets/4fac691f-5303-46fa-bcd4-40506158aeed)
- Yêu cầu POST
- Mục đích Gửi dữ liệu mới lên server để tạo mới.
![image](https://github.com/user-attachments/assets/7b59e2f6-8fb0-40ac-bc83-d78486c6269f)
- Yêu cầu PUT
- Mục đich Cập nhật toàn bộ dữ liệu một mục đã có.
![image](https://github.com/user-attachments/assets/99f2d9e6-82dc-4220-95c2-ddd7860a0d78)
-Yêu cầu DELETE
Mục đích Xóa dữ liệu khỏi server.
![image](https://github.com/user-attachments/assets/fee09f85-4b1c-4d45-8b82-9333e21f2402)


