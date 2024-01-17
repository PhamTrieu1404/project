# SWP391

# Software Requirement Specification

# Artix

# Table of Contents

    *Quy trình 1: ( đăng kí tài khoản User)

• Gửi form cho Guest đăng kí

• Sdt

• Email

• Mật khẩu

• Nhập lại Mật khẩu

• Tự động cấp roleid là user

    *Quy trình 2: ( kiểm tra người dùng, login)

• Lấy thông tin người dùng

• Kiểm tra xem là guest hay user để cấp quyền cho người dùng

• Nếu là guest không có quyền mua bán hay đăng các tác phẩm lên web

• User hoặc Admin có quyền tạo sản phẩm thêm bớt xoá….(Chỉ có admin có quyền chỉnh sửa quyền User.)
webweb
\*Quy trình 3: ( quản lý tác phẩm )

    *Quy trình 4 ( lấy chi tiết sản phẩm)

• Cửa hàng gửi thông tin chi tiết tác phẩm cho khách hàng trong 1 trang web mới

• Tên

• Thông tin

• Đánh giá

• Add wishlist

    *Quy trình 5 ( quản lý cart)

• Tạo giỏ hàng nếu giỏ hàng trống

• Thêm vào giỏ hàng (detail to cart)

• Tên sản phẩm

• Xoá sản phẩm

• Cập nhật giỏ hàng khi user điều chỉnh thêm bớt

• Xoá toàn bộ giỏ hàng

• Chuyển sang thanh toán

    *Quy trình 6 ( quản lý thanh toán )

• Cửa hàng cho phép khách hàng chọn hình thức thanh toán bằng nhiều hình thức:

• Trực tiếp nhắn tin với họa sĩ: Nhắn tin trao đổi trực tiếp với họa sĩ để thanh toán

• Gián tiếp: Thanh toán online qua app ngân hàng hoặc các app như MOMO,ZaloPay,..

• Áp dụng mã giảm giá

• Hủy hình thức thanh toán

• Kiểm tra thanh toán thành công chưa do bên phía công ty chấp nhận thanh toán gửi về ( nếu thành công chuyển về trang chi tiết thanh toán và hiện popup thanh toán thành công tới khách hàng/ thất bại chuyển lại trang giỏ hàng và hiện popup thất bại)

    *Quy trình 7 ( Tạo sản phẩm mới, chỉnh sửa (kiểm tra user quy trình 2))

• Tạo sản phẩm

• Tên sp

• Hình ảnh

• Category

• Price

• Chỉnh sửa sản phẩm

• Lấy khoá sp

• Chỉnh sửa tên hình ảnh

• Chọn category (Select)

• Price …

• Xoá sản phẩm

• Lấy khoá sp

=> chỉ ẩn sản phẩm ko xoá vì dính khoá ngoại

• Kiểm tra xác nhận thay đổi hoặc xác nhận tạo mới, xoá

Note: Coupon

• Giảm giá lấy khoá từ product id

• Kiểm tra xem product có chấp nhận sử dụng mã giảm giá hay ko

• Mặc định khi tạo product thì product luôn chấp nhận giảm giá nếu ko chập nhận thì vào cài đặt sp r update lại

![image](https://github.com/Vuhainam64/SWP391/assets/87472661/47876a4a-8137-4672-aedf-95e4071ad776)

# User Authorization

![image](https://github.com/Vuhainam64/SWP391/assets/87472661/2487c63d-8715-4b56-bf14-43fb3d2733a5)

![image](https://github.com/Vuhainam64/SWP391/assets/87472661/da27fd06-9b70-4ec8-915a-1bd1e9191f7f)

# Functional complexity analysis

![Functional complexity analysis](https://github.com/Vuhainam64/SWP391/assets/87472661/55614953-6c11-4662-9c00-1bd7acc3795c)

# Mô Hình EDR

![EDR](https://github.com/Vuhainam64/SWP391/assets/87472661/c2ef66aa-fede-4a4d-9462-04b02f822b11)
