# Data Science Final Project
# Thành viên nhóm:
- Nguyễn Thị Tình - 1612703
- Trang Trung Hoàng Phúc - 1612521
# Ý tưởng:
- Dự đoán giá laptop dựa vào cấu hình
# Động lực:
- Giúp người dùng đánh giá xem có nên mua một cái laptop hay không vì bây giờ có rất nhiều cửa hàng laptop bán cùng một loại máy nhưng nhiều mức giá khác nhau. Module này sẽ giúp người dùng có một cái nhìn tổng quan về các cửa hàng đó dựa vào giá mà module gợi ý, từ đó đưa ra quyết định mua máy (vì giá của laptop còn phụ thuộc vào chế độ bảo hàng, uy tín cửa hàng...)
# Dữ liệu:
- Lấy dữ liệu từ Amazon.com
- Có hơn 9000 laptop (chưa clean dữ liệu)
- Lọc ra 24 thuộc tính có liên quan (có thể giảm đi sau quá trình clean dữ liệu)
    - **Screen Size**: Kích thước màn hình
    - **Screen Resolution**: Độ phân giải màn hình
    - **Processor**: Bộ vi xử lý (có thể chia ra 2 thuộc tính con là tốc độ và tên của chip xử lý)
    - **RAM**: Bộ nhớ RAM
    - **Hard Drive**: Ổ đĩa cứng
    - **Graphics Coprocessor**: Card đồ họa
    - **Chipset Brand**: Hãng sản xuất vi xử lý
    - **Card Description**: Loại card đồ họa (card rời hay là onboard)
    - **Number of USB 3.0 Ports**: Số cổng USB 3.0 (có rất ít laptop có thông tin này, khoảng 10%)
    - **Average Battery Life (in hours)**: Thời gian pin trung bình (có rất ít laptop có thông tin này, khoảng 30%)
    - **Brand Name**: Hãng sản xuất
    - **Series**: Dòng máy
    - **Operating System**: Hệ điều hành
    - **Item Weight**: Trọng lượng
    - **Product Dimensions**: Kích thước sản phẩm
    - **Item Dimensions L x W x H**: Kích thước sản phẩm chính xác
    - **Processor Brand**: Hãng sản xuất chip
    - **Processor Count**: Số chip xử lý
    - **Flash Memory Size**: Kích thước bộ nhớ Flash (khoảng 30% laptop có thông tin này)
    - **Hard Drive Interface**: Loại ổ cứng
    - **Hard Drive Rotational Speed**: Tốc độ quay ổ cứng (khoảng 20% laptop có thông tin này)
    - **Optical Drive Type**: Ổ đĩa CD (khoảng 10% laptop có thông tin này)
    - **Batteries**: Thông tin pin (khoảng 50% laptop có thông tin này)
    - **Date First Available**: Thời gian ra mắt
- Vấn đề: Có nhiều cột không có dữ liệu, sẽ tìm cách để thêm vào hoặc bỏ các dòng không có dữ liệu đó đi