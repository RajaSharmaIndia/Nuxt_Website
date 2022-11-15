<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <footer>
                        <div class="content">
                            <div class="left box">
                                <div class="upper">
                                    <div class="topic">About us</div>
                                    <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ex!</p>
                                </div>
                                <div class="lower">
                                    <div class="topic">Contact us</div>
                                    <div class="email">
                                        <a href="#"><i class="fas fa-envelope"></i>main2raja.india@gmail.com</a>
                                    </div>
                                </div>
                            </div>
                            <div class="middle box">
                                <div class="topic">Our Services</div>
                                <div><a href="#" class="text-secondary">Home</a></div>
                                <div><a href="#" class="text-secondary">Blog</a></div>
                                <div><a href="#" class="text-secondary">About</a></div>
                                <div><a href="#" class="text-secondary">Service</a></div>
                                <div><a href="#" class="text-secondary">Privacy Policy</a></div>
                            </div>
                            <div class="right box">
                                <div class="topic">Subscribe us</div>
                                <form action="#">
                                    <div class="media-icons">
                                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                                        <a href="#"><i class="fab fa-instagram"></i></a>
                                        <a href="#"><i class="fab fa-twitter"></i></a>
                                        <a href="#"><i class="fab fa-youtube"></i></a>
                                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </footer>
                    <hr />
                    <div class="bottom">
                        <p class="text-center">Copyright © 2020 <a href="#">RajaSharmaIndia</a> All rights reserved</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TheFooter'
}
</script>

<style scoped>
footer {
    bottom: 0;
    left: 0;
    background: white;
}

footer .content {
    margin: auto;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

footer .content p,
a {
    color: black;
}

footer .content .box {
    width: 33%;
    transition: all 0.4s ease;
}

footer .content .topic {
    font-size: 22px;
    font-weight: 600;
    color: #fff;
    margin-bottom: 16px;

}

footer .content p {
    text-align: justify;
}

footer .content .lower .topic {
    margin: 24px 0 5px 0;
}

footer .content .lower i {
    padding-right: 16px;
}

footer .content .middle {
    padding-left: 80px;
}

footer .content .middle a {
    line-height: 32px;
}

footer .content .right input[type="text"] {
    height: 45px;
    width: 100%;
    outline: none;
    color: #d9d9d9;
    background: #000;
    border-radius: 5px;
    padding-left: 10px;
    font-size: 17px;
    border: 2px solid #222222;
}

footer .content .right input[type="submit"] {
    height: 42px;
    width: 100%;
    font-size: 18px;
    color: #d9d9d9;
    background: #eb2f06;
    outline: none;
    border-radius: 5px;
    letter-spacing: 1px;
    cursor: pointer;
    margin-top: 12px;
    border: 2px solid #eb2f06;
    transition: all 0.3s ease-in-out;
}

.content .right input[type="submit"]:hover {
    background: none;
    color: #eb2f06;
}

footer .content .media-icons a {
    font-size: 16px;
    height: 45px;
    width: 45px;
    display: inline-block;
    text-align: center;
    line-height: 43px;
    border-radius: 5px;
    border: 2px solid #222222;
    margin: 30px 5px 0 0;
    transition: all 0.3s ease;
}

.content .media-icons a:hover {
    border-color: #eb2f06;
}

footer .bottom {
    width: 100%;
    text-align: right;
    color: #d9d9d9;
    padding: 0 40px 5px 0;
}

footer .bottom a {
    color: #eb2f06;
}

footer a {
    transition: all 0.3s ease;
}

footer a:hover {
    color: #eb2f06;
}

@media (max-width:1100px) {
    footer .content .middle {
        padding-left: 50px;
    }
}

@media (max-width:950px) {
    footer .content .box {
        width: 50%;
    }

    .content .right {
        margin-top: 40px;
    }
}

@media (max-width:560px) {
    footer {
        position: relative;
    }

    footer .content .box {
        width: 100%;
        margin-top: 30px;
    }

    footer .content .middle {
        padding-left: 0;
    }
}
</style>