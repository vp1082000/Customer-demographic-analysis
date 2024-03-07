
# Customer demographic analysis

__Database__
__aum.csv__|Thông tin tổng tài sản mà khách hàng nắm giữ|
---|---
customer_id|Mã số định danh của khách hàng
amount|Tổng tài sản khách hàng nắm giữ

__cust.csv__|thông tin về phân khúc và nơi ở của khách hàng
---|---
customer_id|Mã số định danh của khách hàng
segment|Phân khúc khách hàng
province_city|Tỉnh/thành phố nơi khách hàng sinh sống

__prod_holding.csv__|thông tin về các sản phẩm mà khách hàng sử dụng
---|---
customer_id|Mã số định danh của khách hàng
prod_ca|Sản phẩm tài khoản thanh toán
prod_td|Sản phẩm tiền gửi có kỳ hạn
prod_credit_card|Sản phẩm thẻ tín dụng


1. Đổi tên cột customer_id thành cust_id

2. Số lượng và Tỷ trọng khách hàng theo từng phân khúc là bao nhiêu?

Cấu trúc bảng kết quả:
Segment|Number Of Customers|Proportion (%)
---|---|---

3. Khách hàng của từng phân khúc tập trung chủ yếu ở những tỉnh, thành phố nào? Sắp xếp theo thứ tự từ lớn nhất đến nhỏ nhất của các cột Regular, Silver, Gold. 

Cấu trúc bảng kết quả:
Province/City |Regular |Silver |Gold
---|---|---|---

4. AUM của khách hàng (Min, Q25, Q50, Q75, Q90, Max, Mean) giữa các phân khúc là như thế nào? (tạo bảng và vẽ box plot cho 3 segment) 

Cấu trúc bảng kết quả:
Segment| Min|Q25 |Q50 |Q75 |Q90 |Max |Mean 
---|---|---|---|---|---|---|---

5. Tỷ lệ nắm giữ các sản phẩm Credit Card, Current Account, Term Deposit của tập khách hàng Regular là như thế  nào?

Cấu trúc bảng kết quả:
Product |No of customers using product|No of customers not using product |Product penetration rate
---|---|---|---
