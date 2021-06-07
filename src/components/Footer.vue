<template>
    <div class="container_footer">

        <div class="container_footer_first">
            <div class="cols">
                <div>
                    <h6>DC COMICS</h6>
                    <nav>
                        <ul>
                            <li>
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">Tv</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                        </ul>
                    </nav>
                    <h6>SHOP</h6>
                    <nav>
                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC collectibles</a>
                            </li>
                        </ul>
                    </nav>
                </div>
                <div>
                    <h6>DC</h6>
                    <nav>
                        <ul>
                            <li>
                                <a href="#">Terms Of Use</a>
                            </li>
                             <li>
                                <a href="#">Privacy Policy (New)</a>
                            </li>
                             <li>
                                <a href="#">Ad Choices</a>
                            </li>
                             <li>
                                <a href="#">Advertising</a>
                            </li>
                             <li>
                                <a href="#">Jobs</a>
                            </li>
                             <li>
                                <a href="#">Subscriptions</a>
                            </li>
                             <li>
                                <a href="#">Talent WorkShop</a>
                            </li>
                             <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                             <li>
                                <a href="#">Ratings</a>
                            </li>
                             <li>
                                <a href="#">Shop Help</a>
                            </li>
                             <li>
                                <a href="#">Contact Us</a>
                            </li>
                        </ul>
                    </nav>
                </div>
                <div>
                    <h6>SITES</h6>
                    <nav>
                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">Mad Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC Kids</a>
                            </li>
                            <li>
                                <a href="#">DC Universe</a>
                            </li>
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
            <div class="image">
                <!-- <img src="../assets/img/dc-logo-bg.png" alt="logo"> -->
            </div>
        </div>

        <div class="container_footer_second">
            <div class="link">
                <a href="#">SING-UP NOW!</a>
            </div>
            <div class="icons">
                <h4>FOLLOW US</h4>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>

    .container_footer_first {
        background: url("../assets/img/footer-bg.jpg");
        display: flex;
        justify-content: space-around;
    }

    .image {
        background: url("../assets/img/dc-logo-bg.png");
        height: 300px;
        background-size: cover;
        width: 300px;
    }

    .cols {
        display: flex;
        padding: 40px;
    }

    ul {
        list-style: none;
    }

    li a {
        text-decoration: none;
        color: lightgray;
        padding: 5px 20px;
    }

    li a:hover {
        text-decoration: underline;
    }

    h6 {
        color: white;
        text-align: center;
        font-size: 14px;
        padding-top: 10px;
    }

    .container_footer_second {
        background-color: #303030;
        padding: 20px;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .link {
        padding: 10px;
        border: 2px solid #0282f9;
        background-color: #303030;
        cursor: pointer;
    }

    a {
        color: white;
        text-decoration: none;
        font-size: 12px;
    }

    .icons {
        display: flex;
    } 

    h4 {
        color: #0282f9;
        line-height: 42px;

    }

    .icons img {
        height: 22px;
        margin: 10px;
        cursor: pointer;
    }

</style>