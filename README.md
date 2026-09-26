# th
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Thực hành Bảng trong CSS</title>
    <style>
        /* Thiết lập đường viền và gộp viền bảng thành một đường duy nhất */
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
        }

        /* Đặt chiều rộng bảng là 100% */
        table {
            width: 100%;
        }

        /* Đặt chiều cao cho thẻ th là 50px */
        th {
            height: 50px;
            background-color: #2c3e50;
            color: white;
            text-align: left; /* Căn lề trái nội dung trong th */
        }

        /* Thiết lập padding khoảng cách nội dung và đường viền */
        th, td {
            padding: 12px;
        }

        /* Căn chỉnh theo chiều dọc xuống dưới (bottom) cho các phần tử td */
        td {
            vertical-align: bottom;
            height: 60px;
        }
    </style>
</head>
<body>

    <h2>Ví dụ về Bảng trong CSS</h2>

    <table>
        <tr>
            <th>Mã sinh viên</th>
            <th>Họ và tên</th>
            <th>Lớp</th>
        </tr>
        <tr>
            <td>DTC245300153</td>
            <td>Sinh viên IT</td>
            <td>cnttk23n</td>
        </tr>
        <tr>
            <td>DTC245300154</td>
            <td>Nguyễn Văn A</td>
            <td>cnttk23n</td>
        </tr>
    </table>

</body>
</html>
