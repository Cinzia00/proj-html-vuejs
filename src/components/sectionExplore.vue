<template>
    <section class="section-bg">
        <div class="container-section">
            <div class="p-description">
                <h3 class="color-green">Let's Dream Big Together</h3>
                <h1 class="title">Explore How can I help you</h1>
            </div>
            <div class="row-card d-flex py-5">
                <div class="card image-card" style="width: 18rem;" v-for="el in cards">
                    <img :class="image-explore" :src=el.image class="card-img-top" alt="...">
                    <div class="card-body px-0">
                        <h1> {{ el.title }} </h1>
                        <p class="card-text text-card"> {{ el.text }} </p>
                        <p class="discover-now">
                            <a href="">Discover now
                                <i class="fa-solid fa-arrow-right-long"></i>
                            </a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container-section">
            <div class="p-description">
                <h3 class="color-green">Let's Dream Big Together</h3>
                <h1 class="title">Explore How can I help you</h1>
            </div>
            <div class="image-section d-flex">
                <div class="position-rel">
                    <div class="box-image">
                        <img class="image" src="/course-02-443x600.jpg" alt="">
                    </div>
                    <a href="#">
                        <div class="position-abs">
                            <p class="price"> $40.oo </p>
                            <h2 class="position-ab-title">Learning to Write as a Professional Author </h2>
                        </div>
                    </a>
                </div>
                <div class="position-rel">
                    <div class="box-image">
                        <img src="/stock-full-hd-03-443x600.jpg" alt="">
                    </div>
                    <a href="#">
                        <div class="position-abs">
                            <p class="price">Free</p>
                            <h2 class="position-ab-title">Customer-centric Info-Tech Strategies</h2>
                        </div>
                    </a>
                </div>
                <div class="position-rel">
                    <div class="box-image">
                        <img src="/stock-full-hd-04-443x600.jpg" alt="">
                    </div>
                    <a href="#">
                        <div class="position-abs">
                            <p class="price">$19.oo</p>
                            <h2 class="position-ab-title">Open Programming Courses for Everyone: Python</h2>
                        </div>
                    </a>
                </div>
                <div class="position-rel">
                    <div class="box-image">
                        <img src="/stock-full-hd-06-443x600.jpg" alt="">
                    </div>
                    <a href="">
                        <div class="position-abs">
                            <p class="price">$26.oo</p>
                            <h2 class="position-ab-title">Academic Listening and Note-taking</h2>
                        </div>
                    </a>
                </div>
            </div>
            <div class="p-description info-view">
                <p>Take the control their life back and start doing thinghs to make their <br> dream come true.
                    <a class="link" href="">View all courses
                        <i class="fa-solid fa-arrow-right-long"></i>
                    </a>
                </p>
            </div>
        </div>
    </section>
</template>


<script>

export default {
    name: 'sectionExplore',

    data() {
        return {
            cards: [
                {
                    image: '/home-business-service-slide-01-480x298.jpg',
                    title: 'Consultative training',
                    text: 'With a coach addressing multiple issues that are off balance, affecting your business in various unconsidered ways.'
                },
                {
                    image: '/home-business-service-slide-02-480x298.jpg',
                    title: 'Real Deal Coaching',
                    text: 'Brings an exceptionally powerful opportunity. Being able to accept, to work with that opportunity.'
                },
                {
                    image: '/home-business-service-slide-03-480x298.jpg',
                    title: 'Advisor Training Program',
                    text: 'Getting high quality, entrepeneur mindset driven online business coaching, is what is needed.'
                },
            ],
            // cardsInfo: [
            //     {
            //         image: '/course-02-443x600.jpg',
            //         price: '$40.oo',
            //         subTitle: 'Learning to Write as a Professional Author'
            //     },
            //     {
            //         image: '/stock-full-hd-03-443x600.jpg',
            //         price: 'Free',
            //         subTitle: 'Customer-centric Info-Tech Strategies'
            //     },
            //     {
            //         image: '/stock-full-hd-04-443x600.jpg',
            //         price: '$19.oo',
            //         subTitle: 'position-ab-title">Open Programming Courses for Everyone: Python'
            //     },
            //     {
            //         image: '/stock-full-hd-06-443x600.jpg',
            //         price: '$26.oo',
            //         subTitle: 'Academic Listening and Note-taking'
            //     },
            // ]
        }
    }
}

</script>


<style lang="scss" scoped>
.container-section {
    padding-top: 125px;
    padding-bottom: 100px;
}

.title {
    font-size: 45px;
    font-weight: bold;
}

.image-card {
    padding: 0;
    width: 23.5rem !important;
}

.row-card {
    justify-content: center;
    gap: 30px;
    text-align: center;

    h1 {
        font-size: 1.5rem;
        padding-top: 2rem;
    }

    .text-card {
        font-size: 0.9rem;
        padding: 10px 25px 10px;
        color: #797979;
    }
}

.discover-now {
    border-top: 1px solid #eceeef;
    margin-top: auto;
    padding-top: 15px;
    color: #20AD96;
    font-size: 13px;
    font-weight: bold;
}

.discover-now:hover {
    font-size: 12px;
}


.box-image {

    img {
        border-radius: 5px;
        width: 100%;

    }
}

.image-section {
    display: flex;
    justify-content: center;
    gap: 30px;
    padding-top: 50px;
}

.position-rel {
    position: relative;
    font-weight: bold;
    width: calc(100% / 4);

    .position-abs {
        position: absolute;
        left: 0;
        bottom: 0;
        padding: 20px;
        color: white;
        font-size: 20px;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .price {
        color: #20AD96;
    }

    .position-ab-title {
        font-size: 23px;
        line-height: 1.8rem;
        font-weight: bold;
    }
}

.info-view {
    margin-top: 50px;
    line-height: 2rem;

    p {
        line-height: 2rem;
        color: #797979;
    }

    .link {
        color: black;
        font-weight: bold;
    }

    .link:hover {
        color: #20AD96;
    }
}


// .card-img-top:hover {
//     border-radius: 20px;
//     transform: scale(1.1);
// }

</style>