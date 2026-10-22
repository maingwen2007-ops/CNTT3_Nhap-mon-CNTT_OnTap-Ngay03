# BÀI LÀM – ÔN TẬP NGÀY 3

- **Họ tên: Lê Anh Duy**
- **Lớp: CNTT3**
- **[Link repository](https://github.com/maingwen2007-ops/CNTT3_Nhap-mon-CNTT_OnTap-Ngay03)**
- **Hệ điều hành (Windows/macOS): Windows**

## Bài 1. README.md

> README.md được chấm trực tiếp trên file `README.md` ở thư mục gốc. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Ít nhất 2 heading cấp 2
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Danh sách đánh số ít nhất 3 bước
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [x] Blockquote nhắc không upload `.env`

## Bài 2. Excel

- > Công thức được chấm trực tiếp trên file `data/hoc_phi_thang_10.xlsx`.
 
  - =VLOOKUP(C6, KhoaHoc!$A$2:$C$8, 2, FALSE)
  -  =VLOOKUP(C4, KhoaHoc!$A$2:$C$8, 3, FALSE)
- **Số dòng còn hiển thị sau khi lọc (câu d): 8**
- **Câu e – Vì sao vùng tra cứu cần dấu $:**
  -   Dấu `$` giúp bảng dữ liệu nguồn  không bị dịch chuyển khi copy hoặc kéo công thức xuống các dòng bên dưới. 
  -  Nếu bỏ `$` và kéo công thức xuống, vùng tra cứu sẽ bị lệch, dẫn đến các mã khóa học ở dòng trên cùng sẽ bị bỏ sót khỏi vùng tìm kiếm, làm công thức trả về lỗi `#N/A`.

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
