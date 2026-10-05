# ☕ CAFÉ ANH VIỆT SÀI GÒN — LANDING PAGE NHƯỢNG QUYỀN CAFÉ TOGO

Trang Landing Page độc lập quảng bá mô hình **Nhượng Quyền Café Togo 0 Đồng Rủi Ro — CAFÉ ANH VIỆT SÀI GÒN**, tích hợp khu vực showcase combo máy pha cà phê **Gemilai CRM 3200B & Máy xay HC-600**, bảng tính toán điểm hòa vốn / ROI trực tiếp cho đối tác và danh mục trang thiết bị chuẩn hóa.

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
    │   └── franchise-3d.js       # Logic hiển thị vật dụng, bảng giá & Engine tính toán ROI
    └── images/
        ├── logo_dsg_chuan.png    # Logo chuẩn
        ├── logo_dsg.png
        ├── dsg_banner.png
        └── ...                   # Bộ tài nguyên hình ảnh thương hiệu đi kèm
```

---

## 🚀 Tính Năng Chính
1. **Showcase Máy Pha Gemilai CRM 3200B & Máy Xay HC-600:**
   - Trưng bày trực quan hình ảnh combo máy pha chuyên nghiệp 15-Bar chuẩn Ý, chiết xuất 20s/ly, công suất 250 ly/ngày.
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
