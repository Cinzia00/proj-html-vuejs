<template>
    <section class="section">
        <div class="container">
            <div class="d-flex info-youtube">
                <div class="position-rel">
                    <div class="box-image">
                        <img src="/home-business-video-poster-670x450.jpg" alt="">
                    </div>
                    <div class="position-ab">
                        <img src="/icon-youtube-play.png" alt="">
                    </div>

                </div>
                <div>
                    <h2 class="title">To Thrive In Business Today, You'll Need a Good Plan</h2>
                    <ul>
                        <li>
                            <h2 class="title-bg">How can we help?</h2>
                            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Possimus quam ipsa est cum.
                                Accusantium maxime, odit eligendi ipsam quibusdam cupiditate!</p>
                        </li>
                        <li>
                            <h2 class="title-bg">Why would I need a business COACH?</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui alias voluptates quia ad rerum
                                nesciunt, placeat omnis illo. Iusto perferendis perspiciatis reiciendis pariatur vitae et.
                            </p>
                        </li>
                        <li>
                            <h2 class="title-bg">What is one-on-one coaching?</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum saepe recusandae expedita
                                facilis, sint modi nulla quos dolore, nihil natus voluptatibus nemo maxime atque laboriosam.
                            </p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <img src="/maxcoach-shape-07.png" alt="">
    </section>
</template>

<style lang="scss" scoped>
.section {
    background-color: #323043;
    background-image: url('/background-map-dots-top-right-transparent.png');
    background-repeat: no-repeat;
    background-position: right;
    color: white;
}

.position-rel {
    position: relative;
}
    .box-image {
        margin-right: 30px;
        width: 700px;
    
        .position-ab {
            position: absolute;
            left: 0;
            bottom: 0;
            // transform: translate(-50% -50%);
        }
    }

.info-youtube {
    gap: 15px;
}

.title {
    width: 435px;
    font-weight: bold;
    font-size: 2.6rem;
}

.title-bg {
    color: #20AD96;
    font-size: 24px;
    font-weight: 100;
}

li {

    p {
        font-size: 14px;
        border-bottom: 2px solid #797979;
        padding: 20px 0;
    }
}</style>