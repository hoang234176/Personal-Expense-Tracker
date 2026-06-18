# 💰 Personal Expense Tracker - Quản lý chi tiêu cá nhân

Một ứng dụng di động theo dõi thu chi cá nhân được phát triển bằng **Flutter**, sở hữu giao diện người dùng hiện đại, trực quan và tốc độ phản hồi nhanh. 

Dự án này tập trung vào việc xử lý logic nội bộ, quản lý luồng dữ liệu (State Management) và lưu trữ cục bộ (Local Storage), mang lại trải nghiệm mượt mà mà không yêu cầu kết nối mạng.

## ✨ Tính năng nổi bật

- **Mô phỏng Xác thực người dùng (Local Auth):** Hỗ trợ đăng nhập, đăng ký và quản lý phiên người dùng an toàn bằng bộ nhớ cục bộ.
- **Quản lý Giao dịch (CRUD):** Dễ dàng thêm, sửa, xóa các khoản Thu nhập (Income) và Chi tiêu (Expense).
- **Phân loại thông minh:** Hỗ trợ nhiều danh mục (Ăn uống, Tiền điện, Đi lại, Mua sắm, v.v.) với giao diện chọn trực quan.
- **Thống kê & Trực quan hóa dữ liệu:** - Biểu đồ tròn (Pie Chart) linh động theo tỷ lệ chi tiêu.
  - Theo dõi tổng thu, tổng chi và tự động tính toán số dư hiện tại.
- **Hỗ trợ Dark/Light Theme (Nếu có, hoặc ghi: UI/UX hiện đại, tối giản):** Thiết kế thân thiện, dễ nhìn, tối ưu cho trải nghiệm di động.

## 📸 Ảnh chụp màn hình

<div align="center">
  <img src="docs/screenshots/Screen Shot 2026-06-18 at 12.19.35.png" width="200" style="margin: 5px;"/>
  <img src="docs/screenshots/Screen Shot 2026-06-18 at 12.20.11.png" width="200" style="margin: 5px;"/>
  <img src="docs/screenshots/Screen Shot 2026-06-18 at 12.20.36.png" width="200" style="margin: 5px;"/>
  <img src="docs/screenshots/Screen Shot 2026-06-18 at 12.21.10.png" width="200" style="margin: 5px;"/>
  <img src="docs/screenshots/Screen Shot 2026-06-18 at 12.21.31.png" width="200" style="margin: 5px;"/>
</div>

## 🛠 Công nghệ & Kiến trúc sử dụng

Dù không sử dụng REST API hay Backend, dự án vẫn được tổ chức với kiến trúc rõ ràng để đảm bảo khả năng mở rộng:

- **Framework:** Flutter / Dart
- **Local Database:** `SharedPreferences`
- **Cấu trúc thư mục:** Được tổ chức theo mô hình `MVC` giúp tách biệt rõ ràng giữa logic giao diện (UI) và xử lý dữ liệu.

## 🚀 Cài đặt và Chạy thử

Vì ứng dụng hoạt động hoàn toàn độc lập (Standalone), bạn có thể dễ dàng clone và chạy ngay lập tức:

1. Clone repository:
   ```bash
   git clone https://github.com/hoang234176/Personal-Expense-Tracker.git