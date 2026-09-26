# th
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Thực hành Danh sách trong CSS</title>
    <style>
        /* 1. Định kiểu cho danh sách không có thứ tự (ul) */
        ul.styled-ul {
            list-style-type: square; /* Đổi ký hiệu thành hình vuông */
            list-style-position: inside; /* Đặt ký hiệu bên trong lề */
            color: #2c3e50; /* Đổi màu chữ toàn bộ danh sách */
        }

        /* Định kiểu riêng cho từng mục li */
        ul.styled-ul li {
            background-color: #ecf0f1;
            margin: 5px 0;
            padding: 8px;
        }

        /* 2. Định kiểu cho danh sách có thứ tự (ol) */
        ol.styled-ol {
            list-style-type: upper-roman; /* Dùng số La Mã in hoa: I, II, III... */
            color: #d35400;
        }
    </style>
</head>
<body>

    <h2>Bài thực hành: Danh sách trong CSS</h2>

    <h3>Danh sách không có thứ tự (ul)</h3>
    <ul class="styled-ul">
        <li>Học thuộc tính list-style-type</li>
        <li>Tìm hiểu vị trí list-style-position</li>
        <li>Thực hành đổi màu sắc danh sách</li>
    </ul>

    <h3>Danh sách có thứ tự (ol)</h3>
    <ol class="styled-ol">
        <li>Bước một: Tạo cấu trúc HTML</li>
        <li>Bước hai: Viết mã CSS trang trí</li>
        <li>Bước ba: Kiểm tra kết quả</li>
    </ol>

</body>
</html>
