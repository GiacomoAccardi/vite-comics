<script>
export default {
    data (){
        return{
            links: [
                {
                    label: 'CHARACTERS',
                    url: '#',
                    current: false,
                },
                {
                    label: 'COMICS',
                    url: '#',
                    current: false,
                },
                {
                    label: 'MOVIES',
                    url: '#',
                    current: false,
                },
                {
                    label: 'TV',
                    url: '#',
                    current: true,
                },
                {
                    label: 'GAMES',
                    url: '#',
                    current: false,
                },
                {
                    label: 'COLLECTABLES',
                    url: '#',
                    current: false,
                },
                {
                    label: 'VIDEOS',
                    url: '#',
                    current: false,
                },
                {
                    label: 'FANS',
                    url: '#',
                    current: false,
                },
                {
                    label: 'NEWS',
                    url: '#',
                    current: false,
                },
                {
                    label: 'SHOP',
                    url: '#',
                    current: false,
                },
            ]
        }
    }
}
</script>

<template>
    <header>
        <div class="container">

            <div class="d-flex justify-content-between align-items-center">

                <!--logo-->
                <img src="../assets/img/dc-logo.png" />

                <!--Container menù-->
                <ul class="d-flex justify-content-evenly"> 
                    <li v-for="link, index in links" :key="index" :class="link.current ? 'active' : '' ">
                        <a :href="link.url">{{ link.label }}</a>
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
            li {

                a {
                    color: black;
                    font-size: 10pt;
                    margin: 0 15px 0 15px;

                }
    
                
            }
        }
    
    }

    .active {
        color: rgb(20, 122, 255);
        border-bottom: 5px solid rgb(20, 122, 255) ;
    }
}

</style>