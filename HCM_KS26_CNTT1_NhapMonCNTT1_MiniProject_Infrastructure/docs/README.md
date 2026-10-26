# Hệ thống quản trị hạ tầng GreenTech

Hệ thống lưu trữ dữ liệu, tự động hóa xử lý nhật ký lỗi (log) và quản lý tài nguyên phần cứng cho các trạm cảm biến IoT ngoài trang trại.

## Hướng dẫn chạy script (Code Block)

Để kích hoạt robot lọc log, mở Terminal (hoặc CMD), đứng ở thư mục gốc của dự án và chạy các lệnh sau:

```cmd
cd scripts
auto_report.bat
```
## Checklist kiểm tra thiết bị (Task List)
[ ]Kiểm tra trạng thái kết nối mạng của toàn bộ 100 trạm cảm biến.

[ ]Xác nhận script auto_report.bat đã xuất file bao-cao-su-co.txt vào thư mục backup/.

[ ] Kiểm tra dung lượng RAM của các trạm không vượt ngưỡng 90%.

[ ] Đối soát mã linh kiện mới thay thế vào file Excel quan-ly-thiet-bi.xlsx.
## Bảng thông số phần cứng (Table)
|Mã Trạm|Tên Thiết Bị|Loại Lưu Trữ|Dung Lượng RAM|Ngày Lắp Đặt|
|----|----|----|----|----|
|TRAM-01|Server Controller Alpha|SSD 512GB|16GB|10/01/2026|
|TRAM-02|Node Gateway Beta|Thẻ nhớ 64GB|4GB|15/02/2026|
|TRAM-03|Edge Computing Core|SSD 256GB|8GB|20/03/2026|