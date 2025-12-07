<!-- info section -->
<section class="info_section">
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="info_contact">
                    <h5>للإتصال المباشر</h5>
                    <div>
                        <div class="img-box">
                            <img src="images/location.png" width="18px" alt="" />
                        </div>
                        <p>Address</p>
                    </div>
                    <div>
                        <div class="img-box">
                            <img src="images/phone.png" width="12px" alt="" />
                        </div>
                        <p>+01 1234567890</p>
                    </div>
                    <div>
                        <div class="img-box">
                            <img src="images/mail.png" width="18px" alt="" />
                        </div>
                        <p>demo@gmail.com</p>
                    </div>
                </div>
            </div>

            <div class="col-md-3">
                <div class="info_social">
                    <h5>وسائل التواصل الاجتماعي</h5>
                    <div class="social_box">
                        <a href="">
                            <img src="images/fb.png" alt="" />
                        </a>
                        <a href="">
                            <img src="images/twitter.png" alt="" />
                        </a>
                        <a href="">
                            <img src="images/linkedin.png" alt="" />
                        </a>
                        <a href="">
                            <img src="images/youtube.png" alt="" />
                        </a>
                    </div>
                </div>
            </div>

            <div class="col-md-3">
                <div class="info_info">
                    <h5>معلومات أخرى</h5>
                    <p>ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt</p>
                </div>
            </div>

            <div class="col-md-3">
                <div class="info_links">
                    <h5>Useful Link</h5>
                    <ul>
                        <li>
                            <a href=""> There are many </a>
                        </li>
                        <li>
                            <a href=""> variations of </a>
                        </li>
                        <li>
                            <a href=""> passages of </a>
                        </li>
                        <li>
                            <a href=""> Lorem Ipsum </a>
                        </li>
                        <li>
                            <a href=""> available, but </a>
                        </li>
                        <li>
                            <a href=""> the i </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- end info_section -->

<!-- footer section -->
<section class="container-fluid footer_section">
    <div class="container">
        <p>
            &copy; <span id="displayYear"></span> All Rights Reserved By
            <a href="https://html.design/">Free Html Templates</a>
        </p>
    </div>
</section>

<!-- end  footer section -->

<style>
    .info_section {
        background-color: #0f2480;
        color: #ffffff;
        padding: 90px 0 45px 0;
    }

    .info_section h5 {
        margin-bottom: 25px;
        font-size: 24px;
    }

    .info_section .info_links ul {
        padding: 0;
    }

    .info_section .info_links ul li {
        list-style-type: none;
    }

    .info_section .info_links ul li a {
        color: #ffffff;
    }

    .info_section .info_contact .img-box {
        width: 35px;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-pack: center;
        -ms-flex-pack: center;
        justify-content: center;
    }

    .info_section .info_contact p {
        margin: 0;
    }

    .info_section .info_contact > div {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        margin: 20px 0;
    }

    .info_section .info_contact > div img {
        height: auto;
        margin-right: 12px;
    }

    .info_section .info_social h5 {
        text-align: center;
    }

    .info_section .info_social .social_box {
        margin-top: 35px;
        width: 100%;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        flex-direction: column;
        gap: 20px;
        align-items: center;
    }

    .info_section .info_social .social_box a {
        margin-right: 25px;
    }
</style>
