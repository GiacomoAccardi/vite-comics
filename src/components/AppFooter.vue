<script>
export default {
    
}
</script>

<template lang="">
    <footer>
        <div class="foot-up">
            <div class="container">

                <div class="content d-flex">
                    <div class="column-50 d-flex">
                        <div class="list-container"> 
                            <h5>DC COMICS</h5>
                            <ul>
                                <li><a>Characters</a></li>
                                <li><a>Comics</a></li>
                                <li><a>Movies</a></li>
                                <li><a>TV</a></li>
                                <li><a>Games</a></li>
                                <li><a>Videos</a></li>
                                <li><a>News</a></li>
                            </ul>
                            <h5>SHOP</h5>
                            <ul>
                                <li><a>Shop DC</a></li>
                                <li><a>Shop DC Collectables</a></li>
                            </ul>
                        </div>
        
                        <div class="list-container"> 
                            <h5>DC</h5>
                            <ul>
                                <li><a>Terms Of Use</a></li>
                                <li><a>Privacy Policy (New)</a></li>
                                <li><a>Ad Choices</a></li>
                                <li><a>Advertising</a></li>
                                <li><a>Jobs</a></li>
                                <li><a>Subscriptions</a></li>
                                <li><a>Talent Workshops</a></li>
                                <li><a>CPSC Certificates</a></li>
                                <li><a>Ratings</a></li>
                                <li><a>Shop Help</a></li>
                                <li><a>Contact Us</a></li>
                            </ul>
                        </div>
        
                        <div class="list-container"> 
                            <h5>SITES</h5>
                            <ul>
                                <li><a>DC</a></li>
                                <li><a>MAD Magazine</a></li>
                                <li><a>DC Kids</a></li>
                                <li><a>DC Universe</a></li>
                                <li><a>DC Power Visa</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
    
            </div>
        </div>

        <div class="foot-down"> 
            <div class="container"> 
                <div class="content d-flex align-items-center justify-content-between"> 
                    
                    <button>SING-UP NOW!</button>

                    <div class="logos-box d-flex align-items-center">
                        <span>FOLLOW US</span>
                        <img src="../assets/img/footer-facebook.png" />
                        <img src="../assets/img/footer-periscope.png" />
                        <img src="../assets/img/footer-pinterest.png" />
                        <img src="../assets/img/footer-twitter.png" />
                        <img src="../assets/img/footer-youtube.png" />
                    </div>

                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
    footer{

        background-image: url(../assets/img/footer-bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;

        .foot-up{
            height: 450px;
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position: 80%;

            .list-container{
                margin: 50px 40px 0 0;

    
                h5{
                    color: white;
                }
                ul{
                    margin-left: -30px;
                }
                li{
                    color: rgb(142, 142, 142);
                }
            }
        }

        .foot-down{
            background-color: rgb(44, 44, 44);
            height: 109px;

            .content{
                padding: 30px 0 30px 0;

                button{
                    color: white;
                    padding: 10px;
                    background-color: rgb(44, 44, 44) ;
                    border: 2px solid rgb(20, 122, 255);
                }

                .logos-box{
                    span{
                        color: rgb(20, 122, 255);
                        font-weight: bolder;
                        margin-right: 20px;
                    }

                    img{
                        margin-right: 20px;
                    }
                }
            }
        }

    }
</style>