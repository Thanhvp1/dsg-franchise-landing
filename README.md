# ☕ ĐẤT SÀI CAFÉ — LANDING PAGE NHƯỢNG QUYỀN TO-GO & TRẠM 3D GEMILAI CRM 3200B

Trang Landing Page độc lập quảng bá mô hình **Nhượng Quyền Cà Phê To-Go 0 Đồng Rủi Ro**, tích hợp trạm mô phỏng 3D tương tác máy pha **Gemilai CRM 3200B**, cốc Cà Phê Muối Đất Sài 3 tầng và công cụ tính toán điểm hòa vốn / ROI trực tiếp cho đối tác.

---

## 📁 Cấu Trúc Thư Mục Độc Lập

```text
landing-page/
├── index.html                    # Trang chính (Landing Page hoàn chỉnh)
├── nhuong-quyen.html             # Bản sao định danh (tiện đối chiếu)
├── README.md                     # Hướng dẫn sử dụng & đẩy lên GitHub
├── .gitignore                    # Bỏ qua các file tạm hệ thống
└── assets/
    ├── franchise/
    │   ├── franchise-landing.css # Toàn bộ hệ thống giao diện, responsive & themes
    │   └── franchise-3d.js       # Engine 3D Three.js máy pha Gemilai & Logic ROI
    └── images/
        ├── logo_dsg_chuan.png    # Logo chuẩn Đất Sài Café
        ├── logo_dsg.png
        ├── dsg_banner.png
        └── ...                   # Bộ tài nguyên hình ảnh thương hiệu đi kèm
```

---

## 🚀 Tính Năng Chính
1. **Trạm 3D Gemilai CRM 3200B Tương Tác:**
   - Xoay 360°, chế độ khung lưới Tech Mesh, quét Laser phân tích, hiệu ứng khói áp suất.
   - Nút mô phỏng chu trình chiết xuất Espresso 15-Bar với đồng hồ cơ đo áp suất, màn hình OLED PID hiển thị thông số và dòng chảy cà phê.
   - Cốc Cà Phê Muối To-Go 3 tầng thực tế kèm sleeve thương hiệu Đất Sài.
2. **Hệ Thống Gói Nhượng Quyền & Bảng Tính ROI:**
   - Chi tiết gói Khởi Nghiệp QCFM 5 (6 Triệu), Gói Inox QCFM 10 (10 Triệu), Gói Pha Máy Espresso và Gói Thuê Quầy Bán Thử 15k/ngày.
   - Công cụ tính toán doanh thu, chi phí hạt nhập 10 TẶNG 1, định mức 60 ly/kg (pha máy) và 40 ly/kg (pha phin).
3. **Chính Sách Hoàn Vốn & Cam Kết 0 Rủi Ro:**
   - Cam kết hoàn vốn 100%, hỗ trợ 50% chi phí vận hành tháng đầu, chuyển giao công thức độc quyền.

---

## 🛠️ Hướng Dẫn Đẩy Lên GitHub Repository Mới

Khi bạn muốn xuất bản Landing Page này lên một kho lưu trữ GitHub độc lập riêng biệt:

1. Mở Terminal / PowerShell tại thư mục `landing-page`:
   ```bash
   cd landing-page
   ```

2. Khởi tạo kho Git mới:
   ```bash
   git init
   git add .
   git commit -m "feat: Khoi tao Landing Page Nhuong Quyen Dat Sai Cafe & 3D Gemilai"
   git branch -M main
   ```

3. Liên kết với Repository mới của bạn trên GitHub (thay URL bên dưới bằng link repo mới của bạn):
   ```bash
   git remote add origin https://github.com/<tai-khoan-cua-ban>/<ten-repo-moi>.git
   ```

4. Đẩy mã nguồn lên:
   ```bash
   git push -u origin main
   ```

5. *(Tùy chọn)* Bật **GitHub Pages** trong mục `Settings -> Pages -> Deploy from a branch -> main / root` để website chạy trực tiếp trên Internet hoàn toàn miễn phí.
