# BÀI LÀM – ÔN TẬP NGÀY 1
-   Họ tên: Phạm Vũ Tuấn Kiệt
-   Lớp:CNTT2
-   link repository:
-   Hệ điều hành (Windows/macOS): window
## Phần A. Tổ chức thư mục bằng GUI
> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.
## Phần B. Thao tác bằng CLI
### Các lệnh đã chạy (B1–B7)
```
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> pwd
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> Get-ChildItem -Force
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv .\Lich_Hoc.txt .\docs\
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv .\Logo_Trung_Tam.PNG .\media\
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cp .\media\Logo_Trung_Tam.PNG .\archive\
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_201.tmp
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_202.tmp
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\logs\
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs> Get-ChildItem
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\docs\
PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> Get-ChildItem -Recurse -Force
```
### Kết quả B1 (pwd)
```
Path
----
C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh 
```
### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)
 Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh
```
 Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          10/20/2026  6:30 PM                archive
d----          10/20/2026  7:23 PM                data
d----          10/20/2026  7:28 PM                docs
d----          10/20/2026  7:29 PM                logs
d----          10/20/2026  7:33 PM                media
-----          10/19/2026  9:40 AM             83 .env
-a---          10/19/2026  7:45 AM          13559 Anh_Lop_Hoc.JPG
-a---          10/19/2026  7:08 AM            902 bai_lam_ngay1.md

    Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 7:40 AM           5184 Logo_Trung_Tam.PNG

    Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 7:40 AM           5070 Hoc_Vien_Khoa_3.xlsx

    Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 7:40 AM             67 Lich_Hoc.txt

    Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 7:40 AM           1072 Access_log.log

    Directory: C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 7:40 AM           5184 Logo_Trung_Tam.PNG

PS C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh>
```
## Tự chấm (điền sau khi có đáp án)
-   **Điểm tự chấm:** ..../100
-   **Lỗi mình đã mắc và cách sửa:**