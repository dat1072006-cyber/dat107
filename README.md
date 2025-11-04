# dat107
web giới thiệu về bản thân
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="Nguyễn Bá Anh Đạt, portfolio, sinh viên, Đại Nam, cá nhân, website cá nhân" />
    <meta name="description" content="Xin chào! Mình là Nguyễn Bá Anh Đạt - Sinh viên Đại Nam, yêu thích công nghệ và lập trình." />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="./assets/css/style.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" crossorigin="anonymous" />
    <!-- Favicon -->
    <link id='favicon' rel="shortcut icon" href="./assets/images/favicon.png" type="image/x-png">
    <title>Portfolio | Nguyễn Bá Anh Đạt</title>
</head>
<body oncontextmenu="return false">

<!-- navbar starts -->
<header>
    <a href="/" class="logo"><i class="fas fa-user-graduate"></i> Đạt</a>
    <div id="menu" class="fas fa-bars"></div>
    <nav class="navbar">
        <ul>
            <li><a class="active" href="#home">Trang chủ</a></li>
            <li><a href="#about">Giới thiệu</a></li>
            <li><a href="#education">Học vấn</a></li>
            <li><a href="#contact">Liên hệ</a></li>
        </ul>
    </nav>
</header>
<!-- navbar ends -->

<!-- hero section starts -->
<section class="home" id="home">
    <div id="particles-js"></div>
    <div class="content">
        <h2>Xin chào,<br/> Mình là <span>Nguyễn Bá Anh Đạt</span></h2>
        <p>Mình là một <span class="typing-text">Sinh viên</span></p>
        <a href="#about" class="btn"><span>Giới thiệu</span>
            <i class="fas fa-arrow-circle-down"></i>
        </a>
    </div>
    <div class="image">
        <img draggable="false" class="tilt" src="./assets/images/hero.png" alt="Nguyễn Bá Anh Đạt">
    </div>
</section>
<!-- hero section ends -->

<!-- about section starts -->
<section class="about" id="about">
    <h2 class="heading"><i class="fas fa-user-alt"></i> Về <span>Bản thân</span></h2>
    
    <div class="row">
        <div class="image">
            <img draggable="false" class="tilt" src="./assets/images/profile2.jpg" alt="Nguyễn Bá Anh Đạt">
        </div>
        <div class="content">
            <h3>Mình là Nguyễn Bá Anh Đạt</h3>
            <span class="tag">Sinh viên</span>
            
            <p>Xin chào! Mình là sinh viên trường Đại học Đại Nam.  
            Mình yêu thích công nghệ, đặc biệt là lập trình web và phát triển phần mềm.  
            Mục tiêu của mình là không ngừng học hỏi và phát triển bản thân để trở thành một lập trình viên giỏi trong tương lai.</p>
            
            <div class="box-container">
                <div class="box">
                    <p><span>Email: </span> nguyenbaanhdat1072006@gmail.com</p>
                    <p><span>Địa chỉ: </span> Dư Dụ, Thanh Thùy, Thanh Oai, Hà Nội</p>
                    <p><span>Số điện thoại: </span> 0989 026 599</p>
                </div>
            </div>
            
            <div class="resumebtn">
                <a href="#" target="_blank" class="btn"><span>Resume</span>
                    <i class="fas fa-chevron-right"></i>
                </a>
            </div>
        </div>
    </div>
</section>
<!-- about section ends -->

<!-- education section starts -->
<section class="education" id="education">
  <h1 class="heading"><i class="fas fa-graduation-cap"></i> Học <span>Vấn</span></h1>
  <p class="qoute">"Giáo dục là nền tảng vững chắc nhất để xây dựng tương lai."</p>

  <div class="box-container">
      <div class="box">
          <div class="image">
              <img draggable="false" src="./assets/images/educat/college.jpg" alt="Đại Nam University">
          </div>
          <div class="content">
              <h3>Sinh viên Đại học Đại Nam</h3>
              <p>Chuyên ngành: Công nghệ thông tin</p>
              <h4>2025 - 2029 | Đang học</h4>
          </div>
      </div>
  </div>
</section>
<!-- education section ends -->

<!-- contact section starts -->
<section class="contact" id="contact">
  <h2 class="heading"><i class="fas fa-headset"></i> Liên <span>Hệ</span></h2>

  <div class="container">
    <div class="content">
      <div class="image-box">
        <img draggable="false" src="./assets/images/contact1.png" alt="">
      </div>
      <form id="contact-form">
          <div class="form-group">
              <div class="field">
                  <input type="text" name="name" placeholder="Họ và tên" required>
                  <i class='fas fa-user'></i>
              </div>
              <div class="field">
                  <input type="email" name="email" placeholder="Email" required>
                  <i class='fas fa-envelope'></i>
              </div>
              <div class="field">
                  <input type="text" name="phone" placeholder="Số điện thoại">
                  <i class='fas fa-phone-alt'></i>
              </div>
              <div class="message">
                  <textarea placeholder="Tin nhắn" name="message" required></textarea>
                  <i class="fas fa-comment-dots"></i>
              </div>
          </div>
          <div class="button-area">
              <button type="submit">
                  Gửi <i class="fa fa-paper-plane"></i>
              </button>
