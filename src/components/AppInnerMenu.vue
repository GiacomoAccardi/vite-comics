<script>
export default {
    data (){
        return{
            cards: [
                {
                    label: 'DIGITAL COMICS',
                    image: '../assets/img/buy-comics-digital-comics.png',
                    href: '#',
                },
                {
                    label: 'DC MERCHANDISE',
                    image: '../assets/img/buy-comics-merchandise.png',
                    href: '#',
                },
                {
                    label: 'SUBSCRIPTION',
                    image: '../assets/img/buy-comics-subscriptions.png',
                    href: '#',
                },
                {
                    label: 'COMIC SHOP LOCATOR',
                    image: '../assets/img/buy-comics-shop-locator.png',
                    href: '#',
                },
                {
                    label: 'DC POWER VISA',
                    image: '../assets/img/buy-dc-power-visa.svg',
                    href: '#',
                },
            ]
        }
    },
    methods: {
        buildingImagePath(imageName) {
            const imageURL = new URL( imageName, import.meta.url);
            return imageURL.href;
        }
    },
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
                            <img :src="buildingImagePath(card.image)" />
                        </div>
                        <a :href="card.href">{{card.label}}</a>
                        
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