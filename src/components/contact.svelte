<section class="contact_section">
    <div class="container">
        <div class="heading_container">
            <h2>أرسل لنا رسالة</h2>
        </div>
    </div>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-6 px-0">
                <div class="map_container">
                    <div class="map-responsive">
                        <iframe
                            src="https://www.google.com/maps/embed/v1/place?key=AIzaSyA0s1a7phLN0iaD6-UE7m4qP-z21pH0eSc&q=Eiffel+Tower+Paris+France"
                            width="600"
                            height="300"
                            frameborder="0"
                            style="border:0; width: 100%; height:100%"
                            allowfullscreen></iframe>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-5">
                <div class="form_container">
                    <form action="">
                        <div>
                            <input type="text" placeholder="الإسم" />
                        </div>
                        <div>
                            <input type="email" placeholder="عنوان إلكتروني" />
                        </div>
                        <div>
                            <input type="text" placeholder="رقم الهاتف" />
                        </div>
                        <div>
                            <input type="text" class="message-box" placeholder="رسالة قصيرة" />
                        </div>
                        <div class="d-flex">
                            <button> OK </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>

<style>
    .contact_section {
        position: relative;
    }

    .contact_section .heading_container {
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        margin-bottom: 40px;
    }

    .contact_section .container-fluid {
        background-color: #0f2480;
        color: #ffffff;
    }

    .contact_section .form_container {
        padding: 45px 0 45px 15px;
    }

    .contact_section input {
        width: 100%;
        border: none;
        background-color: #ffffff;
        outline: none;
        color: #252525;
        margin-top: 25px;
        padding: 12px;
    }

    .contact_section input::-webkit-input-placeholder {
        color: #2a2a2c;
    }

    .contact_section input:-ms-input-placeholder {
        color: #2a2a2c;
    }

    .contact_section input::-ms-input-placeholder {
        color: #2a2a2c;
    }

    .contact_section input::placeholder {
        color: #2a2a2c;
    }

    .contact_section input.message-box {
        padding: 45px 12px;
    }

    .contact_section button {
        padding: 10px 65px;
        outline: none;
        border: none;
        color: #ffffff;
        background: #f97616;
        border-radius: 25px;
        margin: 45px 0 0 auto;
        text-transform: uppercase;
    }

    .contact_section .map_container {
        height: 100%;
    }

    .contact_section .map_container .map-responsive {
        height: 100%;
    }
</style>
