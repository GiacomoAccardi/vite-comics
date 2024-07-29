<script>
export default {
    
}
</script>

<template lang="">
    <header>
        <div class="container">

            <div class="d-flex justify-content-between align-items-center">

                <!--logo-->
                <img src="../assets/img/dc-logo.png" />

                <!--Container menù-->
                <ul class="d-flex justify-content-evenly"> 
                    <li>
                        <a href="#"> CHARACTERS </a>
                    </li>

                    <li>
                        <a href="#"> COMICS </a>
                    </li>

                    <li>
                        <a href="#"> MOVIES </a>
                    </li>

                    <li>
                        <a href="#"> TV </a>
                    </li>

                    <li>
                        <a href="#"> GAMES </a>
                    </li>

                    <li>
                        <a href="#"> COLLECTABLES </a>
                    </li>

                    <li>
                        <a href="#"> VIDEOS </a>
                    </li>

                    <li>
                        <a href="#"> FANS </a>
                    </li>

                    <li>
                        <a href="#"> NEWS </a>
                    </li>

                    <li>
                        <a href="#"> SHOP </a>
                    </li>
                </ul>


            </div>

        </div>
    </header>
</template>

<style scoped>
    
header{

    .container {

        padding: 20px;
    
        img{
            width: 75px;
        }
    
        ul{
            list-style-type: none;
    
            li {
                
                a {
                    text-decoration: none;
                    color: black;
                    font-size: 10pt;
                    margin: 0 15px 0 15px;
                }
    
                
                &:hover {
                    color: rgb(20, 122, 255);
                    border-bottom: 5px solid rgb(20, 122, 255) ;
                }
            }
        }
    
    }
}

</style>