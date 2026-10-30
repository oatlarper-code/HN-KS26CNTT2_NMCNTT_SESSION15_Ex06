# 5.Yêu cầu đầu ra

`Folder`
```
Green-tech
|
|-- (1)Lưu-trữ-code-cảm-biến
|   |_Quản lý phiên bản code(Git,Github,Gitlab)
|   |_Chia sẻ code nội bộ đội ngũ kỹ thuật
|   |_Kiểm soát truy cập an toàn
|
|-- (2)Chia-sẻ-báo-cáo-cho-nhà-đầu-tư
|   |_Tạo báo cáo định kì (tiến độ,tài chính,hiệu quả)
|   |_Cổng thông tin riêng cho đầu tư
|   |_Chia sẻ tài liệu trình bày, dữ liệu trực quan
|
|-- (3)Kênh-trao-đổi-cho-đội-ngũ-kỹ-thuật
    |_Trao đổi tức thì, thảo luận nhóm(Slack,Teams,Discord)
    |_Quyền: Chỉ có những người đảm nhiệm làm việc kỹ thuật
```

|Thư mục|Nhà đầu tư|Đối tác cung cấp thiết bị|Đội ngũ kỹ thuật|Trưởng nhóm
|-|-|-|-|-|
Code|No Access|No Access|Editor|Owner
Report|No Access|No Access|Viewer|Owner
Agrument|No Access|Access|Commenter|Owner
`Channel`
```
Greentech
|
|-- #thông-báo-chung
|   |_Nội dung: Đăng tải các thông tin chính, deadline,...
|   |_Quyền:Admin, Trưởng nhóm
|
|-- #general
|   |_Nội dung: Trao đổi ý kiến với nhiều thành viên khác
|   |_Quyền: Tất cả mọi người
|
|-- #kỹ-thuật
|   |_Nội dung: Thảo luận chuyên sâu về kỹ thuật, Không được nhắn tin lạc chủ đề tránh bị trôi tin nhắn
|   |_Quyền: Chỉ có những người đảm nhiệm làm việc kỹ thuật
|
|-- #giải-trí
    |_Nội dung: Chia sẻ các hình ảnh, thông tin giải trí 
    |_Quyền: Tất cả mọi người
```

- Kiểm thử: Giả định một thành viên lỡ tay xóa sạch folder sensors, hãy trình bày quy trình khôi phục nhanh nhất.
  - Bước 1: Khôi phục trong thùng rác đám mây
  - Bước 2: Xem thông tin của file (File Information)
  - Bước 3: Kiểm tra trong Manage Version và tải xuống file gốc của bài