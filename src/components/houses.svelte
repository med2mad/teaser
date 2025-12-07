<script>
    const x = "شقق رائعة بمدينة الدار البيضاء، بمكان هادىء  يحتوي على جميع المتطلبات ";
    let houses = [
        { img: "s-1.jpg", title: "سكن إقتصادي", text: x },
        { img: "s-3.jpg", title: "منازل فاخرة", text: x },
        { img: "s-6.jpg", title: "شقق سكنية", text: x },
        { img: "s-4.jpg", title: "سكن إقتصادي", text: x },
        { img: "s-5.jpg", title: "شقق سكنية", text: x },
        { img: "s-2.jpg", title: "منازل فاخرة", text: x },
    ];

    // { img: "s-4.jpg", title: "شقق سكنية", text: x },
    // { img: "s-6.jpg", title: "شقة بالدار البيضاء", text: x },
    // { img: "s-2.jpg", title: "منازل فاخرة", text: x },
    // { img: "s-3.jpg", title: "سكن إقتصادي", text: x },
    // { img: "s-2.jpg", title: "شقق سكنية", text: x },
    // { img: "s-1.jpg", title: "شقة بالدار البيضاء", text: x },

    // { img: "s-1.jpg", title: "شقق سكنية", text: x },
    // { img: "s-3.jpg", title: "منازل فاخرة", text: x },
    // { img: "s-6.jpg", title: "سكن إقتصادي", text: x },
    // { img: "s-4.jpg", title: "منازل فاخرة", text: x },
    // { img: "s-5.jpg", title: "سكن إقتصادي", text: x },
    // { img: "s-5.jpg", title: "شقة بالدار البيضاء", text: x },
</script>

<section class="find_section">
    <div class="container">
        <form action="">
            <div class="form-row">
                <div class="col-md-3">
                    <div>
                        <label for="searchplace">المكان</label>
                        <select id="searchplace" class="form-control">
                            <option>--</option>
                            <option>وسط المدينة</option>
                            <option>الألفة</option>
                            <option>الحي الحسني</option>
                            <option>سيدي معروف</option>
                            <option>ليساسفة</option>
                            <option>الرحمة</option>
                        </select>
                    </div>
                </div>
                <div class="col-md-3">
                    <div>
                        <label for="searchtype">النوع</label>
                        <select id="searchtype" class="form-control">
                            <option>--</option>
                            <option>شقة</option>
                            <option>عمارة</option>
                            <option>فيلا</option>
                        </select>
                    </div>
                </div>
                <div class="col-md-3">
                    <div>
                        <label for="searchcontract">العقد</label>
                        <select id="searchcontract" class="form-control">
                            <option>--</option>
                            <option>الكراء</option>
                            <option>الشراء</option>
                        </select>
                    </div>
                </div>
                <div class="col-md-2">
                    <button type="submit" class=""> search </button>
                </div>
            </div>
        </form>
    </div>
</section>
<!-- end find section -->

<!-- sale section -->
<section class="sale_section layout_padding-bottom">
    <div class="container-fluid">
        <div class="sale_container">
            {#each houses as house}
                <div class="box">
                    <div class="img-box" style="position: relative;">
                        <svg class="heart" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="presentation" focusable="false"
                            ><path
                                d="m15.9998 28.6668c7.1667-4.8847 14.3334-10.8844 14.3334-18.1088 0-1.84951-.6993-3.69794-2.0988-5.10877-1.3996-1.4098-3.2332-2.11573-5.0679-2.11573-1.8336 0-3.6683.70593-5.0668 2.11573l-2.0999 2.11677-2.0988-2.11677c-1.3995-1.4098-3.2332-2.11573-5.06783-2.11573-1.83364 0-3.66831.70593-5.06683 2.11573-1.39955 1.41083-2.09984 3.25926-2.09984 5.10877 0 7.2244 7.16667 13.2241 14.3333 18.1088z"
                            ></path
                            ></svg>

                        <img src="images/{house.img}" alt="" />
                    </div>
                    <div class="detail-box">
                        <h6>{house.title}</h6>
                        <p>{house.text}</p>
                    </div>
                </div>
            {/each}
        </div>
        <div class="btn-box">
            <a href=""> المزيد </a>
        </div>
    </div>
</section>

<style>
    .find_section {
        -webkit-transform: translateY(-50%);
        transform: translateY(-50%);
    }

    .form-row {
        align-items: flex-end;
        gap: 5px;
        justify-content: space-between;
    }

    .find_section form {
        padding: 10px 45px;
        -webkit-box-shadow: 0px 0px 20px 11px rgba(0, 0, 0, 0.09);
        box-shadow: 0px 0px 20px 11px rgba(0, 0, 0, 0.09);
        background-color: #ffffff;
        border-radius: 25px;
        border: #8f8f8f 1px solid;
    }

    .find_section form .form-control {
        outline: none;
        -webkit-box-shadow: none;
        box-shadow: none;
        border-radius: 0;
        height: 45px;
        margin: 10px 0;
    }

    .find_section form button {
        background-color: #f97616;
        color: #ffffff;
        text-transform: uppercase;
        border: none;
        height: 45px;
        width: 100%;
        margin: 10px 0;
    }

    .col-md-3 {
        text-align: center;
    }
    .col-md-3 select,
    .col-md-2 button {
        margin: 0 !important;
    }
    .col-md-3 label {
        color: #0f2480;
        font-weight: bold;
        font-size: 1.2rem;
    }

    .col-md-3 div {
        display: flex;
        gap: 10px;
        align-items: center;
    }

    .sale_section .sale_container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    .sale_section .sale_container .box .img-box img {
        height: 170px;
        width: 100%;
        transition: transform 0.3s;
    }

    .sale_section .sale_container .box .img-box img:hover {
        transform: scale(1.1);
    }

    .sale_section .sale_container .box .img-box {
        overflow: hidden;
        border-radius: 25px;
    }

    .sale_section .sale_container .box .detail-box {
        margin-top: 10px;
    }

    .sale_section .sale_container .box .detail-box h6 {
        font-weight: bold;
        font-size: 18px;
        text-align: center;
    }
    .sale_section .sale_container .box {
        width: 200px;
    }
    .sale_section .sale_container .box .detail-box p {
        font-size: 01rem;
        text-align: right;
    }

    .heart {
        position: absolute;
        top: 10px;
        right: 10px;
        z-index: 99;
        display: block;
        fill: rgba(0, 0, 0, 0.5);
        height: 24px;
        width: 24px;
        stroke: white;
        stroke-width: 2;
        overflow: visible;
        stroke: white;
        stroke-width: 2;
        fill: rgba(0, 0, 0, 0.5);
    }
</style>
