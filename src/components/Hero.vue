<template>
    <section class="section-hero">
        <div class="container hero-container">
            <div class="row">
                <div class="col-5 descriptio-hero">
                    <h3 class="color-green">New Challenges, New Skills</h3>
                    <h1 class="text-hero">BUILD YOUR OWN LIFE COACHING BUSINESS</h1>
                    <p class="paragraph-hero">Whole-Life Business Coaching for committed entrepreneurs</p>
                    <button class="button-get-started">Get started today</button>
                </div>
                <div class="col avatar-hero">
                    <img src="/home-business-hero-avatar.png" alt="">
                </div>
                <div class="image-world">
                    <img src="/home-business-hero-global-image.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>


<script>

export default {
    name: 'Hero'
}

</script>


<style lang="scss" scoped>
.section-hero {
    position: relative;
    background-color: #EFF2F6;
    z-index: -999;
    
    
    .image-world img {
        position: absolute;
        right: 10%;
        top: 5%;
        z-index: -500;
        animation-name: spin;
        animation-duration: 18000ms;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
    }

    @keyframes spin {
        0% {
            transform: rotate(1turn);
        }
    }

    .hero-container {
        padding: 45px;
    }

    .descriptio-hero {
        padding-top: 135px;
        padding-left: 30px;
    }

    .avatar-hero {
        margin-left: 130px;
    }

    .color-green {
        padding-bottom: 15px;
        font-size: 23px;
    }
}

.text-hero {
    font-weight: bold;
    font-size: 3rem;
    padding-bottom: 24px;
}

.paragraph-hero {
    line-height: 2rem;
    color: #797979;
    font-size: 17px;
    padding-bottom: 14px;
}
</style>