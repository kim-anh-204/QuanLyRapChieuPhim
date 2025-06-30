# 🎬 Quản Lý Rạp Chiếu Phim

Đây là phần mềm **quản lý rạp chiếu phim** được xây dựng bởi Nhóm 9 - CNTT4 - K63 trong môn học **Lập trình trực quan**. Ứng dụng hỗ trợ cả khách hàng lẫn quản lý trong việc đặt vé, theo dõi suất chiếu, doanh thu, và thống kê hoạt động kinh doanh.

---

## 👥 Nhóm thực hiện

| Họ tên               | Mã sinh viên | Công việc chính |
|---------------------|--------------|-----------------|
| Nguyễn Đình Tuấn Anh | 221231039   | Quản lý phim, doanh thu, thiết kế CSDL, vẽ sitemap |
| Trần Văn Giáp        | 221230818   | Giao diện đăng nhập/đăng ký, đặt vé, chỉnh sửa thông tin, thiết kế Figma |
| Nguyễn Tùng Lâm      | 221230892   | Giao diện đăng ký, quản lý suất chiếu, nhân viên, khách hàng, vẽ use-case |
| Trần Kim Anh         | 221230742   | Quản lý phòng chiếu, báo cáo doanh thu, chèn dữ liệu và tổng hợp báo cáo |

---

## 🚀 Công nghệ sử dụng

- **Ngôn ngữ chính**: C#
- **Nền tảng**: WinForms (.NET)
- **Backend**: ASP.NET  
- **Cơ sở dữ liệu**: SQL Server
- **Thư viện hỗ trợ UI**: Bunifu Framework  
- **Biểu đồ, thống kê**: LiveCharts

---

## 🎯 Tính năng chính

### 👤 Đối với khách hàng:
- Đăng ký, đăng nhập tài khoản
- Tìm kiếm phim & đặt vé theo suất chiếu
- Chọn ghế, thanh toán
- Chỉnh sửa thông tin cá nhân

### 🛠 Đối với quản lý:
- Quản lý nhân viên, phòng chiếu, phim, khách hàng
- Tạo và chỉnh sửa suất chiếu
- Theo dõi và thống kê doanh thu theo ngày/tuần/tháng/năm
- Xuất báo cáo doanh thu ra Excel
- Hiển thị biểu đồ:
  - Top 5 thể loại phim được xem nhiều
  - Top 5 suất chiếu bán chạy
  - Top 10 phim được xem nhiều nhất

---

## 🗃️ Cơ sở dữ liệu

Hệ thống sử dụng SQL Server với các bảng chính:

- `PHIM`, `SUATCHIEU`, `PHONGCHIEUPHIM`
- `VEXEMPHIM`, `KHACHHANG`, `NHANVIEN`, `NGUOIDUNG`
- `GHE`, `PHIM_LOAIPHIM`, `LOAIPHIM`

Hệ thống đảm bảo tính toàn vẹn, ràng buộc chặt chẽ giữa các bảng.

---

## 📷 Một số hình ảnh

> _Bạn có thể thêm ảnh tại đây để minh họa: giao diện đăng nhập, quản lý phim, biểu đồ thống kê, đặt vé,..._

```markdown
![Trang đăng nhập](screenshots/login.png)
![Quản lý phim](screenshots/manage_movies.png)
![Biểu đồ doanh thu](screenshots/revenue_chart.png)
