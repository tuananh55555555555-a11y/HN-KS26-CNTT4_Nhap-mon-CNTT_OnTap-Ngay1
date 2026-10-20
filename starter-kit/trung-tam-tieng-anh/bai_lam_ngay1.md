# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Trần Tuấn Anh**
- **Lớp: CNTT4**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
ls
Move-Item .\lich_hoc.txt .\docs\
Move-Item .\anh_lop_hoc.JPG .\media\
Move-Item .\logo_trung_tam.PNG .\media\
Copy-Item .\media\logo_trung_tam.PNG .\archive\
rm .\temp_201.tmp
rm .\temp_202.tmp
cd .\logs\
ls
cd ..\
cd .\docs\
Copy-Item ..\media\anh_lop_hoc.jpg ..\archive
cd ..\
ls
```

### Kết quả B1 (pwd)

```text
Path
----
D:\starter-kit\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
    Directory: D:\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   6:21 PM                archive
d-----        10/20/2026   6:24 PM                data
d-----        10/20/2026   6:29 PM                docs
d-----        10/20/2026   6:24 PM                logs
d-----        10/20/2026   6:31 PM                media
-a----        10/20/2026   6:17 PM             83 .env
-a----        10/20/2026   6:26 PM            899 bai_lam_ngay1.md

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 100/100
- **Lỗi mình đã mắc và cách sửa:**
