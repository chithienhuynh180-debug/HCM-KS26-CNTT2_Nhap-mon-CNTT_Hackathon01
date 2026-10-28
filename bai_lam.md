# BÀI LÀM – HACKATHON 01

- **Mã đề:** 13
- **Họ tên:Huỳnh Chí Thiện** 
- **Lớp:CNTT2** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS): Window** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
cd C:\Users\Admin\Downloads\starter-kit\ngoai-ngu-website
ls 
mv ".\Thoi Khoa Bieu.txt" docs
mv '.\Logo Trung Tam Ngoai Ngu.PNG' media
cp '.\media\Logo Trung Tam Ngoai Ngu.PNG' backup
rm *.tmp
cat *.log
cd ..
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
2026-03-28 08:18:28 [INFO] Giao vien cap nhat diem danh
2026-03-28 08:21:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 08:24:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:27:28 [INFO] Thanh toan hoc phi thanh cong
2026-03-28 08:30:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:33:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:36:28 [INFO] Gui email xac nhan lop
2026-03-28 08:39:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:42:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:45:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 08:48:28 [INFO] Hoc vien xem lich khai giang
2026-03-28 08:51:28 [WARNING] Thoi gian tai trang cham
2026-03-28 08:54:28 [WARNING] Video bai giang dung luong lon
2026-03-28 08:57:28 [WARNING] Thoi gian tai trang cham
2026-03-28 09:00:28 [INFO] Giao vien cap nhat diem danh
2026-03-28 09:03:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 09:06:28 [INFO] Hoc vien xem lich khai giang
2026-03-28 09:09:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 09:12:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 09:15:28 [INFO] Thanh toan hoc phi thanh cong
```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
(ls -Filter *.log -Recurse | Select-String "ERROR" | Measure-Object -Line).Lines
ni logs\daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-03-28 08:24:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:30:28 [ERROR] Het thoi gian cho (timeout)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [x] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
(ls -Filter *.log -Recurse | Select-String "ERROR" | Measure-Object -Line).Lines

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
6

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dang_ky_hoc_thang_3.xlsx`, không cần ghi vào đây.
