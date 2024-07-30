<script>
export default {
    data (){
        return{
            cards: [
                {
                    label: 'DIGITAL COMICS',
                    image: '../assets/img/buy-comics-digital-comics.png',
                    current: false,
                },
                {
                    label: 'DC MERCHANDISE',
                    image: '../assets/img/buy-comics-merchandise.png',
                    current: false,
                },
                {
                    label: 'SUBSCRIPTION',
                    image: '../assets/img/buy-comics-subscriptions.png',
                    current: false,
                },
                {
                    label: 'COMIC SHOP LOCATOR',
                    image: '../assets/img/buy-comics-shop-locator.png',
                    current: false,
                },
                {
                    label: 'DC POWER VISA',
                    image: '../assets/img/buy-dc-power-visa.svg',
                    current: false,
                },
            ]
        }
    }
}
</script>

<template>
    <div class="wrapper">
        <div class="bg-primary">
            <div class="container">
                <div class="content d-flex justify-content-between">

                    <div
                      class="d-flex align-items-center"
                      v-for="(card, index) in cards"
                      :key="index">

                        <div>
                            <img :src="card.image" />
                        </div>
                        <a href="#">{{card.label}}</a>
                        
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .wrapper{
        position: relative;
        z-index: 1;
    }
    .content{
        padding: 40px 20px 40px 20px;

        img{
           height: 45px;
        }

        a{
            color: white;
            margin-left: 15px;
        }


    }
</style>