# WONDERLAB – Website đồ chơi giáo dục và sáng tạo

## 1. Giới thiệu dự án

WONDERLAB là dự án xây dựng giao diện website thương mại điện tử dành cho cửa hàng đồ chơi giáo dục và sáng tạo, hướng đến trẻ em từ 4–12 tuổi, phụ huynh và người mua quà tặng.

Dự án được thực hiện trong khuôn khổ môn **Phát triển ứng dụng thương mại điện tử**, nhằm thực hành xây dựng website bằng HTML5 và CSS3, tổ chức bố cục giao diện và thiết kế responsive.

## 2. Cấu trúc thư mục

```text
DEMO--MAIN/
├── assets/                 # Hình ảnh, logo, video, font và tài nguyên
├── css/
│   └── style.css           # CSS dùng chung cho các trang
├── docs/                   # Tài liệu và minh chứng dự án
├── index.html              # Trang chủ
├── products.html           # Trang danh sách sản phẩm
├── product-detail.html     # Trang chi tiết sản phẩm
├── about.html              # Trang giới thiệu
├── README.md               # Hướng dẫn dự án
└── .gitignore              # Cấu hình loại trừ tệp Git
```

## 3. Danh sách các trang

| Trang | Tệp | Nội dung chính |
|---|---|---|
| Trang chủ | `index.html` | Giới thiệu cửa hàng, danh mục và sản phẩm nổi bật |
| Danh sách sản phẩm | `products.html` | Hiển thị sản phẩm theo dạng lưới, khu vực bộ lọc và sắp xếp |
| Chi tiết sản phẩm | `product-detail.html` | Hình ảnh, giá, mô tả, thông số và video giới thiệu sản phẩm |
| Giới thiệu | `about.html` | Thông tin về WONDERLAB và định hướng cửa hàng |

## 4. Công nghệ sử dụng

- **HTML5:** Xây dựng cấu trúc nội dung, sử dụng thẻ ngữ nghĩa và tích hợp video.
- **CSS3:** Thiết kế màu sắc, kiểu chữ, khoảng cách và hiệu ứng giao diện.
- **CSS Grid và Flexbox:** Sắp xếp bố cục trang, thanh điều hướng và danh sách sản phẩm.
- **Media Query:** Điều chỉnh giao diện theo kích thước màn hình.
- **Hover, Focus và Transition:** Tạo phản hồi trực quan cho các thành phần tương tác.

Phiên bản bài tập này tập trung vào HTML5 và CSS3, không yêu cầu backend hoặc cơ sở dữ liệu.

## 5. Cách mở và chạy website

1. Tải hoặc sao chép toàn bộ thư mục dự án về máy tính.
2. Mở thư mục bằng Visual Studio Code hoặc trình quản lý tệp.
3. Mở file `index.html` bằng trình duyệt Chrome, Edge hoặc Safari.
4. Sử dụng thanh điều hướng để truy cập các trang còn lại.

Có thể sử dụng tiện ích **Live Server** trong Visual Studio Code để xem và cập nhật giao diện thuận tiện hơn.

Website sử dụng các đường dẫn tương đối đến tài nguyên, vì vậy cần giữ nguyên cấu trúc thư mục khi chạy.

## 6. Cách kiểm tra giao diện responsive

1. Mở website trên Google Chrome.
2. Nhấn `F12` hoặc `Cmd + Option + I` trên macOS để mở Developer Tools.
3. Chọn chế độ mô phỏng thiết bị (*Toggle Device Toolbar*).
4. Lần lượt kiểm tra giao diện ở các kích thước:
   - **1366px:** Màn hình máy tính.
   - **768px:** Máy tính bảng.
   - **390px:** Điện thoại.
5. Quan sát bố cục, hình ảnh, thanh điều hướng, khoảng cách và khả năng đọc nội dung.
6. Kiểm tra cả bốn trang để phát hiện hiện tượng tràn ngang, chồng lấn hoặc hình ảnh hiển thị không phù hợp.

## 7. Những hạn chế hiện tại

- Website chủ yếu phục vụ mục đích trình diễn giao diện tĩnh.
- Các chức năng lọc, sắp xếp và tìm kiếm sản phẩm chưa được xử lý động đầy đủ.
- Giỏ hàng và các nút mua hàng chưa tạo thành quy trình đặt hàng hoàn chỉnh.
- Chưa tích hợp backend, cơ sở dữ liệu hoặc hệ thống thanh toán.
- Một số thao tác tương tác nâng cao cần JavaScript để hoạt động đầy đủ.

---

**Ghi chú:** Đây là sản phẩm học tập, không phải website thương mại điện tử đang vận hành thực tế.