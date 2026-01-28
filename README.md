# GiaBao_0235_NNPTUD

## Mô tả dự án
Ứng dụng web hiển thị danh sách sản phẩm từ API EscuelaJS.

## Yêu cầu
- Copy data JSON từ API
- Convert JSON thành JavaScript objects
- Hiển thị sản phẩm trên giao diện

## API sử dụng
- **Endpoint**: https://api.escuelajs.co/api/v1/products
- **Method**: GET
- **Response**: JSON array chứa danh sách sản phẩm

## Cách sử dụng

1. Mở file `JavaScript/index.html` trong trình duyệt
2. Ứng dụng sẽ tự động fetch dữ liệu từ API
3. Dữ liệu JSON được convert thành JavaScript objects
4. Hiển thị sản phẩm dưới dạng card layout

## Cấu trúc thư mục
```
GiaBao_0235_NNPTUD/
├── JavaScript/
│   ├── index.html      # File HTML chính
│   └── main.json       # File cấu hình API
└── README.md           # File hướng dẫn
```

## Tính năng
- ✅ Fetch dữ liệu từ API
- ✅ Convert JSON thành JavaScript objects
- ✅ Hiển thị sản phẩm với giao diện đẹp
- ✅ Responsive design
- ✅ Xử lý lỗi khi API không khả dụng
- ✅ Hiển thị số lượng sản phẩm

## Công nghệ sử dụng
- HTML5
- CSS3 (Grid Layout, Flexbox)
- JavaScript (ES6+)
- Fetch API