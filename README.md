<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="describtion" content="Website for shopping">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/all.min.css">
    <link rel="stylesheet" href="css/main-theme.css">
    <link rel="stylesheet" href="css/theme1.css">
    <title> shopex </title>
</head>

<body>
    
    <header>
        <div class="container">
            <a href="mainsa.html">
                <div id="brand">
                    <h1>shopex </h1>
                </div>
            </a>
            <nav>
                <ul>
                    <li>
                        <form class="search-box">
                            <input type="search" class="search" placeholder="ابحث عن منتجاتنا">
                            <button>البحث</button>
                        </form>
                    </li>
                    <li class="curent"><a href="mainsa.html"> <i class="fa-solid fa-house"></i> Home </a> </li>
                    <li><a href="salah.html">Log in </a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">About Us </a></li>
                    <li><a href="#">Cart <i class="fa-solid fa-cart-shopping"></i> </a></li>

                </ul>
            </nav>
        </div>
    </header>

    <div class="bo">
        <div class="box">
            <h2>Log In</h2>
            <form method="get" action="mainsa.html">
                <div class="input-box">
                    <input type="text" required>
                    <label>User Name</label>
                </div>
                <div class="input-box">
                    <input type="password" required>
                    <label>password</label>
                </div>
                <input class="sub" type="submit" name="" value="log in">
                <input class="sub" type="submit" name="" value="sign up">
            </form>
        </div>
    </div>

    <div class="footer">
        <div class="container">
            <p>join us</p>
            <div class="social-icons">
                <i class="fa-brands fa-facebook social"></i>
                <i class="fa-brands fa-twitter social"></i>
                <i class="fa-brands fa-instagram social"></i>
                <i class="fa-solid fa-house social"></i>

            </div>
            <p class="copyright">
                copyright 2022 &copy; <span>shopers</span> All rights reserved
            </p>
        </div>
    </div>
    <script src="js/all.min.js"></script>

</body>

</html>
