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
                    <div class="column-50">
                        <div class="bg-logo">
                            <img src="../assets/img/dc-logo-bg.png" />
                        </div>
                    </div>
                </div>
    
            </div>
        </div>
    </footer>
</template>

<style scoped>
    footer{

        .foot-up{
            background-image: url(../assets/img/footer-bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            height: 450px;

            .bg-logo{
                position: relative;


                img{
                   position: absolute;
                   top:-50px;
                }
            }

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



    }
</style>