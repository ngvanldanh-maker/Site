#nhom4
/* style.css */
:root {
    --primary: #0056b3;
    --accent: #f39c12;
    --dark: #2c3e50;
    --light: #ecf0f1;
}

body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    line-height: 1.6;
    background-color: #f4f7f6;
}

/* Menu điều hướng */
nav {
    background: white;
    padding: 15px 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

nav a {
    text-decoration: none;
    color: var(--dark);
    font-weight: bold;
    margin-left: 20px;
    transition: 0.3s;
}

nav a:hover { color: var(--primary); }

/* Banner hiệu ứng */
.hero {
    height: 400px;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                url('https://images.unsplash.com');
    background-size: cover;
    background-position: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    animation: fadeIn 1.5s ease-in;
}

/* Các thẻ nội dung (Cards) */
.container {
    padding: 40px 10%;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

.card img { width: 100%; height: 200px; object-fit: cover; }
.card-body { padding: 20px; }

/* Link liên kết */
.external-links {
    background: var(--dark);
    color: white;
    padding: 40px;
    text-align: center;
}

.external-links a {
    color: var(--accent);
    display: block;
    margin: 10px 0;
    text-decoration: none;
}

/* Hiệu ứng Animation */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Du Lịch Đà Nẵng</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <h2>Đà Nẵng Discovery</h2>
        <div>
            <a href="index.html">Du Lịch</a>
            <a href="am-thuc.html">Ẩm Thực</a>
            <a href="van-hoa.html">Văn Hóa</a>
        </div>
    </nav>
    <div class="hero">
        <h1>DU LỊCH ĐÀ NẴNG</h1>
        <p>Khám phá thành phố của những cây cầu huyền thoại</p>
    </div>
    <div class="container">
        <div class="grid">
            <div class="card">
             (https://github.com/user-attachments/assets/dceea8b3-7830-4be3-a8af-110caf7ce062)   <img src="https://dulichsonitra.com" alt="Cầu Rồng">
                <div class="card-body">
                    <h3>Cầu Rồng</h3>
                    <p>Biểu tượng vươn mình ra biển lớn, phun lửa và nước vào cuối tuần.</p>
                </div>
            </div>
            <div class="card">
              ![1000009089](https://github.com/user-attachments/assets/dea7258e-eb70-42a0-af56-5c06e09b7f6e)
  <img src="https://vcdn1-dulich.vnecdn.net" alt="Bà Nà Hills">
                <div class="card-body">
                    <h3>Bà Nà Hills</h3>
                    <p>Trải nghiệm khí hậu 4 mùa trong ngày và check-in Cầu Vàng.</p>
                </div>
            </div>
        </div>
    </div>
    <section class="external-links">
        <h3>Thông tin hữu ích khác</h3>
        <a href="https://danangfantasticity.com">Cổng du lịch Danang Fantasticity</a>
        <a href="https://www.tripadvisor.com.vn">Top điểm đến trên TripAdvisor</a>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Ẩm Thực Đà Nẵng</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <h2>Đà Nẵng Discovery</h2>
        <div><a href="index.html">Du Lịch</a> <a href="am-thuc.html">Ẩm Thực</a> <a href="van-hoa.html">Văn Hóa</a></div>
    </nav>
    <div class="hero" style="background-image: url('https://mia.vn')">
        <h1>THIÊN ĐƯỜNG ẨM THỰC</h1>
        <p>Đánh thức vị giác với những món ngon miền Trung</p>
    </div>
    <div class="container">
        <div class="grid">
            <div class="card">
             ![1000009090](https://github.com/user-attachments/assets/ae331ba4-ebfa-4b01-9471-7f82edd1287b)
   <img src="https://static-images.vnncdn.net" alt="Mì Quảng">
                <div class="card-body">
                    <h3>Mì Quảng</h3>
                    <p>Sự kết hợp tinh tế giữa sợi mì dai, tôm, thịt và nước dùng đậm đà.</p>
                </div>
            </div>
            <div class="card">
            ![1000009091](https://github.com/user-attachments/assets/4df1515f-3123-427f-a0c5-b3acda853be1)
    <img src="https://statics.vinpearl.com" alt="Bánh tráng thịt heo">
                <div class="card-body">
                    <h3>Bánh tráng cuốn thịt heo</h3>
                    <p>Món ăn dân dã với mắm nêm đặc sản không thể cưỡng lại.</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Văn Hóa Đà Nẵng</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <h2>Đà Nẵng Discovery</h2>
        <div><a href="index.html">Du Lịch</a> <a href="am-thuc.html">Ẩm Thực</a> <a href="van-hoa.html">Văn Hóa</a></div>
    </nav>
    <div class="hero" style="background-image: url('https://baodanang.vn')">
        <h1>VĂN HÓA & CON NGƯỜI</h1>
        <p>Nơi giao thoa giữa truyền thống và hiện đại</p>
    </div>
    <div class="container">
        <div class="grid">
            <div class="card">
                <div class="card-body">
                ![1000009092](https://github.com/user-attachments/assets/36c8a28e-7a3a-4821-9648-98c878445002)
    <h3>Lễ hội Pháo hoa (DIFF)</h3>
                    <p>Sự kiện quốc tế rực rỡ sắc màu bên bờ sông Hàn thơ mộng hàng năm.</p>
                </div>
            </div>
            <div class="card">
                <div class="card-body">
                ![1000009093](https://github.com/user-attachments/assets/519d8d4e-f871-4fc5-bbba-f6c6fbf9ad54)
    <h3>Bảo tàng Điêu khắc Chăm</h3>
                    <p>Nơi lưu giữ linh hồn và di sản kiến trúc Champa độc đáo nhất Việt Nam.</p>
                </div>
            </div>
        </div>
    </div>![1000009088]
    <footer style="text-align: center; padding: 20px; background: #ddd;">
        <p>Liên hệ: <a href="https://danang.gov.vn">Cổng thông tin TP Đà Nẵng</a></p>
    </footer>
</body>
</html>
