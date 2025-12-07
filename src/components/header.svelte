<div class="hero_area">
    <!-- <header class="header_section">
        <div class="container-fluid">
            <nav class="navbar navbar-expand-lg custom_nav-container">
                <a class="navbar-brand" href="index.html">
                    <img src="images/logo.png" alt="" />
                </a>
                <div class="navbar-collapse" id="">
                    <ul class="navbar-nav justify-content-between">
                        <div class="User_option">
                            <li class="">
                                <a class="mr-4" href=""> Login </a>
                                <a class="" href=""> Sign up </a>
                            </li>
                        </div>
                    </ul>
                </div>
            </nav>
        </div>
    </header> -->
    <!-- slider section -->
    <section class="slider_section">
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-4 offset-md-1">
                    <div class="detail-box">
                        <h1 style="text-align: center;">
                            <span> إبحث عن</span> <br />
                            شقة مستقبلك
                        </h1>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- end slider section -->
</div>

<style>
    .custom_nav-container.navbar-expand-lg .navbar-nav .nav-item .nav-link {
        padding: 10px 15px;
        color: #060606;
        text-align: center;
        text-transform: uppercase;
    }

    .custom_nav-container.navbar-expand-lg .navbar-nav .nav-item.active .nav-link,
    .custom_nav-container.navbar-expand-lg .navbar-nav .nav-item:hover .nav-link {
        color: #3554d1;
    }

    .custom_nav-container .nav_search-btn {
        background-image: url(../images/search-icon.png);
        background-size: 17px;
        background-repeat: no-repeat;
        background-position-y: 7px;
        width: 35px;
        height: 35px;
        padding: 0;
        border: none;
    }

    .custom_nav-container {
        z-index: 99999;
        padding: 0;
        height: 80px;
    }

    .custom_nav-container .navbar-toggler {
        outline: none;
    }

    .custom_nav-container .navbar-toggler .navbar-toggler-icon {
        background-image: url(../images/menu.png);
        background-size: 50px;
        width: 30px;
        height: 30px;
    }

    .hero_area {
        background-image: url(../images/hero-bg.jpg);
        position: relative;
        background-repeat: no-repeat;
        background-position: top right;
        background-size: 60% 100%;
    }

    .sub_page .hero_area {
        height: auto;
        background: none;
        background-color: #0f2480;
    }

    .slider_section {
        padding: 75px 0;
        color: #0b0b0b;
    }

    .slider_section .row {
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
    }

    .slider_section .detail-box h1 {
        color: #3554d1;
        font-weight: bold;
        font-size: 4rem;
    }

    .slider_section .detail-box h1 span {
        color: #0f2480;
    }
</style>
