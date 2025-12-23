# 🎄 Noel V2 - Hướng dẫn sử dụng

## 📁 Cấu trúc thư mục

```
hmtl/
├── noel_v2.html          # File chính
├── images/               # Thư mục chứa ảnh của bạn
│   ├── photo1.jpg       # (Ví dụ)
│   ├── photo2.png       # (Ví dụ)
│   └── ...
└── README.md            # File này
```

## 🖼️ Cách thêm ảnh vào thư mục images

### Bước 1: Copy ảnh vào thư mục `images`
- Đặt các file ảnh của bạn vào thư mục `images/`
- Hỗ trợ các định dạng: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`

### Bước 2: Cập nhật danh sách ảnh trong code

Mở file `noel_v2.html` và tìm dòng:

```javascript
const imageFiles = [
    // Add your image filenames here
    // Example: 'photo1.jpg', 'photo2.png', 'photo3.jpg'
];
```

Thêm tên file ảnh của bạn vào mảng này:

```javascript
const imageFiles = [
    'photo1.jpg',
    'photo2.png',
    'family.jpg',
    'christmas2024.png'
];
```

### Bước 3: Mở file HTML trong trình duyệt
- Double click vào `noel_v2.html` hoặc
- Kéo thả file vào trình duyệt

## ⌨️ Phím tắt

| Phím tắt | Chức năng |
|----------|-----------|
| **Ctrl+F** (hoặc Cmd+F) | Thêm ảnh mới từ máy tính |
| **Ctrl+Delete** (hoặc Cmd+Del) | Xóa tất cả ảnh đã lưu trong database |
| **H** | Ẩn/hiện hướng dẫn |

## 💾 Lưu trữ ảnh

### 1. Ảnh từ thư mục `images/`
- Được tải tự động khi mở trang
- Luôn hiển thị khi mở lại
- Hoạt động trên mọi trình duyệt và thiết bị

### 2. Ảnh thêm bằng Ctrl+F
- Được lưu vào IndexedDB của trình duyệt
- Chỉ hiển thị trên trình duyệt đã thêm
- Có thể xóa bằng Ctrl+Delete

## 🎮 Điều khiển bằng cử chỉ tay

- **Nắm tay lại**: Chế độ cây thông (Tree mode)
- **Mở bàn tay**: Chế độ phân tán (Scatter mode)
- **Chụm ngón tay**: Chế độ focus vào 1 ảnh ngẫu nhiên
- **Di chuyển tay**: Xoay các ảnh trong chế độ Scatter

## 🎨 Ví dụ cấu hình

```javascript
const imageFiles = [
    'christmas1.jpg',
    'christmas2.jpg',
    'christmas3.png',
    'family_photo.jpg',
    'santa.png'
];
```

Sau đó copy 5 file ảnh tương ứng vào thư mục `images/`.

## ⚠️ Lưu ý

1. **Tên file phải khớp chính xác** (phân biệt hoa thường trên Linux/Mac)
2. **Đường dẫn tương đối**: Thư mục `images` phải nằm cùng cấp với `noel_v2.html`
3. **Kích thước ảnh**: Nên dùng ảnh có kích thước hợp lý (< 2MB) để trang load nhanh
4. **Định dạng**: Khuyến nghị dùng `.jpg` hoặc `.png`

## 🚀 Khởi động nhanh

1. Copy ảnh vào thư mục `images/`
2. Mở `noel_v2.html` bằng text editor
3. Tìm `const imageFiles = [...]` và thêm tên file ảnh
4. Lưu file và mở trong trình duyệt
5. Thưởng thức! 🎄✨
