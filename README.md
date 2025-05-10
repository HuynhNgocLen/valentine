<!DOCTYPE HTML>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="login.js"></script> 
    <script type="module">
        import { showWelcome } from './showelcome.js';
        document.addEventListener("DOMContentLoaded", showWelcome);
      </script>
      
    <title>GenZ Thời Trang</title>
</head>

<body>
    <header>
        <nav class="thanhngang">
            <div class="logo" style="margin-left: 10px; margin-right: 30px; display: flex; align-items: center;">
                <a href="index.html" style="font-size: 15px; font-weight: bold; white-space: nowrap;">G E N <span style="font-size: 25px;">Z</span></a>
            </div>

            <ul class="thanhnganggiua">
                <ul class="thanhngangtrai">
                    <li><a href="index.html">Trang chủ</a></li>
                    <li><a href="Sanpham.html">Sản phẩm</a></li>
                </ul>
                <ul class="thanhngangphai">
                    <li>
                        <input type="text" placeholder="Tìm kiếm..." class="otimkiem">
                        <button class="timkiem">Tìm Kiếm</button>
                    </li>
                    <li><a href="Giohang.html">🛒</a></li>
                    <li class="dropdown">
                        <a href="#" class="dropbtn">Tài khoản ▼</a>
                        <div class="dropdown-content">
                            <a href="Thongtin.html" id="account-2">Thông tin cá nhân</a>
                            <a href="lichsumua.html" style="margin-left: 20px;">Lịch sử mua hàng</a>
                            <a href="Dangnhap.html" id="account-link">Đăng nhập</a>
                        </div>
                    </li> 
                </ul>
            </ul>

            <div class="thongbao">
                <div class="chaychu" >
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                    <h4><strong>🔥MIỄN PHÍ VẬN CHUYỂN CHO MỌI ĐƠN HÀNG </strong></h4>
                </div>
            </div>
        </nav>
    </header>

    <main>
        <a href="Sanpham.html" style="display: block; width: 90%; margin: auto;">
            <img src="anh/Bia2.png" alt="Hình ảnh" style="width: 100%; height: auto;">
        </a>
        <h1 style="text-align: center;">HÀNG MỚI VỀ</h1>

        <h1 style="text-align: center;">BỘ SƯU TẬP</h1>
        <a href="Sanpham.html" style="display: block; width: 100%; margin: auto;">
            <img src="anh/Bia1.png" alt="Hình ảnh" style="width: 100%; height: auto;">
        </a>
        <h1 style="text-align: center;">HOT🔥</h1>
        <div class="ophai" style="margin:auto; width: 100%;">
            <!-- Sản phẩm 1 -->
            <div class="osanpham">
                <a href="chitietsp.html?id=1" style="text-decoration: none;">
                <div style="color: red; font-size: 20px; display: flex; justify-content: flex-start; text-align: left;">HOT NEW</div>
                <img src="anh/quanbo.jpg" alt="Sản phẩm 1">
                <h3>Quần bò baggy nam ống suông rộng màu xanh nhạt vải bò jeans</h3>
                <p class="price">265.000đ</p>
                    <div class="xemngays">
                        <button class="xemngay">XEM NGAY</button> 
                    </div>
                </a>
            </div>
            <!-- Sản phẩm 2 -->
            <div class="osanpham">
                <a href="chitietsp.html?id=2" style="text-decoration: none;">
                <div class="hot-new">HOT NEW</div>
                <img src="anh/Q1.jpg" alt="Sản phẩm 2">
                <h3>Quần jeans baggy nam dáng dài ống suông rộng phối loang màu cá tính vải bò mềm mại</h3>
                <p class="price">325.000đ</p>
                    <div class="xemngays">
                        <button class="xemngay">XEM NGAY</button> 
                    </div>
                </a>
            </div>
            <!-- Sản phẩm 3 -->
            <div class="osanpham">
            <a href="chitietsp.html?id=3" style="text-decoration: none;">
                <div style="color: red; font-size: 20px; display: flex; justify-content: flex-start; text-align: left;">HOT NEW</div>
                <img src="anh/Q2.jpg" alt="Sản phẩm 3">
                <h3>Quần Jean Nam Ống Rộng Chất Liệu Dày Dặn Phong Cách Đường Phố</h3>
                <p class="price">539.000đ</p>
                    <div class="xemngays">
                        <button class="xemngay">XEM NGAY</button>
                    </div>
                </a>       
            </div>
            <!-- Sản phẩm 4 -->
            <div class="osanpham">
                <a href="chitietsp.html?id=4" style="text-decoration: none;">
                <div style="color: red; font-size: 20px; display: flex; justify-content: flex-start; text-align: left;">HOT NEW</div>
                <img src="anh/Q3.jpg" alt="Sản phẩm 4">
                <h3>Quần jeans baggy nam dáng dài ống suông rộng màu xanh nhạt wash rách gối cá tính</h3>
                <p class="price">295.000đ</p>
                    <div class="xemngays">
                        <button class="xemngay">XEM NGAY</button>
                    </div>
            </a>
            </div>
        </div>
    </main>
    <script>
            
        document.addEventListener("DOMContentLoaded", function () {
                    const nutTimKiem = document.querySelector(".timkiem");
                    const oTimKiem = document.querySelector(".otimkiem");
            
                    nutTimKiem.addEventListener("click", function () {
                        const tuKhoa = oTimKiem.value.trim();
                        if (tuKhoa !== "") {
                            window.location.href = `timkiem.html?q=${encodeURIComponent(tuKhoa)}`;
                        }
                    });
            
                    // Thêm chức năng nhấn Enter
                    oTimKiem.addEventListener("keypress", function (e) {
                        if (e.key === "Enter") {
                            nutTimKiem.click();
                        }
                    });
                });
            </script>
    <script src="fliter.js"></script>
    <script src="timkiem.js"></script> 
    <footer>
        <div class="thongtin">
            <div class="thongtintrai">
                <p>Dám khác biệt, dám tỏa sáng!</p>
                <p>Đặt hàng và thu tiền tận nơi toàn quốc</p>
                <p>Liên hệ: (036) 3348 6045</p>
            </div>
            <div class="thongtinphai">
                <p>Về chúng tôi</p>
                <p>Liên hệ</p>
            </div>
        </div>
        <div class="thongtinduoi">
            <p>© 2025 - Shop Thời Trang Bán Quần Áo GenZ</p>
            <p>Địa chỉ đăng ký kinh doanh: Số 16 Trần Văn Ơn, Phường Phú Lợi, Bình Dương - Điện thoại: (036) 3348 6045 - Email: 2424802010379@student.tdmu.edu.vn</p>
        </div>
    </footer>
</body>
</html>
