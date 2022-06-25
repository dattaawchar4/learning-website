<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="/main logo fevicon icon.png" />
    <link rel="stylesheet" href="a1_HomePage.css">
    <title>Home</title>
</head>

<body>

    <!------------------------ Navigation bar designing ------------------------>

    <div id="container">

        <div id="main-top-items">
            <a href="">
                <img id="main-logo" src="/main logo fevicon icon.png" alt=""></a>
            <a class="top-nav-items top-nav-home" href="/a1_HomePage.html">Home</a>
            <a class="top-nav-items top-nav-codes" href="/demo.html">Codes</a>
            <a class="top-nav-items top-nav-assignments" href="">Assignments</a>
            <a class="top-nav-items top-nav-aboutus" href="/a4_AboutPage.html">About Us</a>
        </div>
        <div class="search-btnand">
            <div id="signlog-btn">
                <input type="button" value="Login" id="login-button">
                <input type="button" value="Signup" id="signup-button">
            </div>
            <div class="search-box">
                <table class="search-box-elements">
                    <tr>
                        <td>
                            <input type="text" placeholder="Search For Languages..." class="search-place">
                        </td>
                        <td><a href="#"><img src="/icons8-search-50.png" alt="search" class="material-icon"></a></td>
                    </tr>
                </table>
            </div>
        </div>
        <!-- adding icon in mobile view -->
        <div id="hamburger-icon" onclick="toggleMobileMenu(this)">
            <div class="bar1"></div>
            <div class="bar2"></div>
            <div class="bar3"></div>
            <ul class="mobile-menu">
                <a class="mobile-menu-items mobile-menu-items-home" href="">Home</a>
                <a class="mobile-menu-items" href="">Codes</a>
                <a class="mobile-menu-items" href="">Assignments</a>
                <a class="mobile-menu-items" href="">About Us</a>
                <a class="signlog-btn-mobile login-btn" href=""><input type="button" value="Login"
                        class="login-btn-1"></a>
                <a class="signlog-btn-mobile" href=""><input type="button" value="Signup" class="signup-btn-1"></a>
            </ul>
        </div>
    </div>



    <!-------------- First page designing ---------------------->

    <div class="first-page-container">
        <div class="first-page-items">
            <div>
                <h1 class="main-page-heading">Welcome To <span class="heading-color">Easy Learn</span></h1>

                <p class="main-page-para">Just see the reference of the code with easy learns, easy learn is making
                    way of fun to writing and thinking about codes and many more programming languages, just search
                    any program you want to search and type that code in your compiler and run without debugging it.
                </p>
            </div>
        </div>
        <div class="first-page-items">
            <img class="main-img" src="/first page img.jpg" alt="">
        </div>
    </div>

    <!----------------------- Second page designing ------------------>

    <div class="second-page">
        <div class="second-page-heading">
            <h3>Courses To Learn</h3>
        </div>
        <div class="second-page-items">
            <div class="second-page-items-boxes "><a href="/demo.html#c-language-op" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-cprogram">C</h4>
                    <img class="second-page-images logo-c-programming" src="/C_logo.png" alt="C Programming">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-cpp-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-cppprogram">C++</h4>
                    <img class="second-page-images logo-cpp-programming" src="/C++ logo.png" alt="C++ Programming">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-java-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-javaprogram">Java</h4>
                    <img class="second-page-images logo-java-programming" src="/java logo.png" alt="Java Programming">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-js-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-javascriptprogram">Java Script</h4>
                    <img class="second-page-images logo-javascript-programming" src="/javascript logo.svg"
                        alt="Java Script Programming">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-html-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-htmlprogram">HTML</h4>
                    <img class="second-page-images logo-html-programming" src="/html logo.png" alt="HTML">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-css-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-cssprogram">CSS</h4>
                    <img class="second-page-images logo-css-programming" src="/CSS3_logo.png" alt="CSS">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-php-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-phpprogram">PHP</h4>
                    <img class="second-page-images logo-php-programming" src="/php logo.png" alt="PHP Programming">
                </a>
            </div>
            <div class="second-page-items-boxes"><a href="/demo.html#code-python-language" class="second-page-decoration">
                    <h4 class="second-page-headings second-page-pythonprogram">Python</h4>
                    <img class="second-page-images logo-python-programming" src="/Python logo.png"
                        alt="Python Programming">
                </a>
            </div>
        </div>
    </div>

    <!------------------- Third page designing (Assignment session) ----------------->

    <div class="third-page">
        <div class="third-page-heading">
            <h3>Assignments</h3>
        </div>
        <div class="third-page-items">
            <div class="third-page-items-boxes "><a href="" class="third-page-decoration">
                    <h4 class="third-page-headings third-page-cprogram">C</h4>
                    <img class="third-page-images logo-c-programming" src="/C_logo.png" alt="C Programming">
                </a>
            </div>
            <div class="third-page-items-boxes"><a href="" class="third-page-decoration">
                    <h4 class="third-page-headings third-page-htmlprogram">HTML</h4>
                    <img class="third-page-images logo-html-programming" src="/html logo.png" alt="HTML Programming">
                </a>
            </div>
            <div class="third-page-items-boxes"><a href="" class="third-page-decoration">
                    <h4 class="third-page-headings third-page-cssprogram">CSS</h4>
                    <img class="third-page-images logo-css-programming" src="/CSS3_logo.png" alt="css Programming">
                </a>
            </div>
            <div class="third-page-items-boxes"><a href="" class="third-page-decoration">
                    <h4 class="third-page-headings third-page-sqlprogram">SQL</h4>
                    <img class="third-page-images logo-sql-programming" src="/sql logo.png" alt="sql Programming">
                </a>
            </div>
        </div>
    </div>
    <br>

    <!------------------------- Last page designing ------------------------>

    <div class="last-page">
        <img src="/main logo fevicon icon.png" alt="logo" class="last-page-img">
        <h5 id="developer-name">
            <p>Developed by</p>
            <p>Dattatray Kashinath Awchar</p>
        </h5>
        </img>
    </div>

    <!-------------------------- Copyright declaration --------------------->

    <div class="last-page-copy-right-declaration ">
        <div class="copy-right-declaration bottom-img-para">
            <img src="/main logo fevicon icon.png" alt="bottom logo" class="bottom-logo">
            <p class="bottom-para">Easy Learn</p>
        </div>
        <div class="copy-right-declaration">
            <p class="copy-right-declaration-para">copyright © 2022 easylearn.com</p>
        </div>
        <div class="copy-right-declaration">
            <a href=""><img src="/instagram logo.png" alt="instagram" class="instagram-logo"></a>
        </div>
    </div>

    <script src="/a1_HomePage.js"></script>

    

</body>

</html>
