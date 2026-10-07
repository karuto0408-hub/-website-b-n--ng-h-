<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Bán Đồng Hồ - Đồ án Thực tập</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
<header class="main-header">
<nav class="top-menu">
<ul>
<li><a href="#home" class="active">TRANG CHỦ</a></li>
<li><a href="#login">ĐĂNG NHẬP</a></li>
<li><a href="#register">ĐĂNG KÝ</a></li>
<li><a href="#add-sp">THÊM SP</a></li>
<li><a href="#catalog">DANH MỤC</a></li>
<li><a href="#products">SẢN PHẨM</a></li>
<li><a href="#orders">ĐƠN HÀNG</a></li>
</ul>
</nav>
</header>
<div class="main-body">
<aside class="sidebar">
<div class="sidebar-title">Danh Mục Sản Phẩm</div>
<ul class="catalog-list">
<li><a href="#">Casio</a></li>
<li><a href="#">Rolex</a></li>
<li><a href="#">Citizen</a></li>
<li><a href="#">Seiko</a></li>
<li><a href="#">Diesel</a></li>
<li><a href="#">Timex</a></li>
</ul>
</aside>
<main class="content">
<section class="section-box">
<h2 class="section-title">Sản Phẩm Nổi Bật</h2>
<div class="product-grid">
<div class="product-card">
<div class="product-img">
<img src="https://via.placeholder.com/200x200?text=Timex+T499059J" alt="Timex T499059J">
</div>
<div class="product-info">
<h3>Timex T499059J</h3>
<p class="origin">Spain</p>
<p class="price">2,990,000 đ</p>
<button class="btn-detail">XEM CHI TIẾT</button>
</div>
</div>
<div class="product-card">
<div class="product-img">
<img src="https://via.placeholder.com/200x200?text=TIMEX+Weekender" alt="TIMEX Weekender T2N651">
</div>
<div class="product-info">
<h3>TIMEX Weekender T2N651</h3>
<p class="origin">Spain</p>
<p class="price">2,560,000 đ</p>
<button class="btn-detail">XEM CHI TIẾT</button>
</div>
</div>
<div class="product-card">
<div class="product-img">
<img src="https://via.placeholder.com/200x200?text=Timex+T49261SU" alt="Timex T49261SU">
</div>
<div class="product-info">
<h3>Timex T49261SU</h3>
<p class="origin">Spain</p>
<p class="price">3,700,000 đ</p>
<button class="btn-detail">XEM CHI TIẾT</button>
</div>
</div>
</div>
</section>
<section class="section-box">
<h2 class="section-title">Form Đăng Nhập</h2>
<form class="custom-form">
<table class="form-table">
<tr>
<td><label for="username">Tên tài khoản</label></td>
<td><input type="text" id="username" placeholder="Nhập tên tài khoản"></td>
</tr>
<tr>
<td><label for="password">Mật khẩu</label></td>
<td><input type="password" id="password" placeholder="Nhập mật khẩu"></td>
</tr>
<tr>
<td colspan="2">
<button type="button" class="btn-action">Đăng nhập</button>
</td>
</tr>
</table>
</form>
</section>
<section class="section-box">
<div class="alert-box">
<span class="alert-text">Thông báo: Thêm sản phẩm [MTP-V005D-1AUDF] vào giỏ hàng thành công</span>
<span class="close-btn">&times;</span>
</div>
<h2 class="section-title">Giỏ Hàng Của Bạn</h2>
<table class="data-table">
<thead>
<tr>
<th>Tên sản phẩm</th>
<th>Số lượng</th>
<th>Giá</th>
<th>Thành tiền</th>
<th>Xóa</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="#" class="item-link">MTP-V005D-1AUDF</a></td>
<td><input type="number" value="1" class="input-qty"></td>
<td>696,255</td>
<td>696,255</td>
<td><a href="#" class="delete-link">Xóa</a></td>
</tr>
<tr>
<td colspan="3" class="text-right"><strong>Tổng tiền</strong></td>
<td colspan="2"><strong class="highlight-price">696,255 đ</strong></td>
</tr>
</tbody>
</table>
<div class="cart-actions">
<button class="btn-action">Mua tiếp sản phẩm</button>
<button class="btn-action">Cập nhật số lượng</button>
</div>
<h3 class="sub-title">Thông tin mua hàng</h3>
<form class="custom-form">
<table class="form-table">
<tr>
<td>Họ tên <span class="required">*</span>:</td>
<td><input type="text" placeholder="Nhập họ tên"></td>
</tr>
<tr>
<td>Số điện thoại <span class="required">*</span>:</td>
<td><input type="text" placeholder="Nhập số điện thoại"></td>
</tr>
<tr>
<td>Địa chỉ <span class="required">*</span>:</td>
<td><textarea rows="3" placeholder="Nhập địa chỉ nhận hàng"></textarea></td>
</tr>
<tr>
<td>Ghi chú:</td>
<td><textarea rows="2" placeholder="Ghi chú thêm..."></textarea></td>
</tr>
<tr>
<td colspan="2">
<button type="button" class="btn-action btn-large">Thanh toán</button>
</td>
</tr>
</table>
</form>
</section>
<section class="section-box product-detail-box">
<div class="detail-left">
<img src="https://via.placeholder.com/300x300?text=MTP-V005D-1AUDF" alt="Casio MTP-V005D-1AUDF">
</div>
<div class="detail-right">
<h2 class="detail-title">MTP-V005D-1AUDF</h2>
<div class="detail-price">696,255 đ</div>
<ul class="specs-list">
<li>Mặt kính khoáng chống nước</li>
<li>Dây đeo bằng thép không gỉ</li>
<li>Chốt gập ba</li>
<li>Giờ hiện hành thông thường</li>
<li>Đồng hồ kim: 3 kim (giờ, phút, giây)</li>
<li>Độ chính xác: ±20 giây một tháng</li>
<li>Tuổi thọ pin xấp xỉ: 3 năm với pin SR626SW</li>
<li>Kích thước vỏ: 47 × 40 × 8.1 mm</li>
<li>Tổng trọng lượng: 90 g</li>
<li><strong>Mã SP:</strong> 5</li>
<li><strong>Xuất xứ:</strong> USA</li>
<li><strong>Loại đồng hồ:</strong> Casio</li>
</ul>
<div class="warranty-badge">✔ Bảo hành 12 tháng</div>
<div class="commitments">
<h4>TẠI SAO NÊN CHỌN ĐỒNG HỒ 24H?</h4>
<ul>
<li>📢 Cam kết đảm bảo hàng chính hãng</li>
<li>💰 Hoàn tiền lại gấp 10 lần nếu phát hiện hàng giả - hàng nhái.</li>
<li>💲 Giá luôn thấp hơn thị trường từ 5-10%.</li>
<li>🛡️ Chế độ bảo hành lên đến 5 năm tại Đồng Hồ 24H.</li>
<li>🔄 Đổi hàng trong 7 ngày - Nếu sai kích cỡ? Không vừa ý?</li>
</ul>
</div>
</div>
</section>
</main>
</div>
<footer class="main-footer">
<p>&copy; 2025 Website Bán Đồng Hồ - Trường Trung Cấp Hà Nội (HACO)[cite: 1]</p>
<p>Địa chỉ: Hà Nội | Hotline: 0123 456 789</p>
</footer>
</div>
<script src="script.js"></script>
</body>
</html>
