<template>
    <section class="section">
        <div class="container">
            <div class="d-flex info-youtube">
                <div>
                    <div class="box-image position-rel">
                        <img src="/home-business-video-poster-670x450.jpg" alt="">
                        <div class="position-ab">
                            <a href="#">
                                <img src="/icon-youtube-play.png" alt="">
                            </a>
                        </div>
                    </div>
                </div>
                <div>
                    <h2 class="title">To Thrive In Business Today, You'll Need a Good Plan</h2>
                    <ul>
                        <li>
                            <h2 class="title-bg more-info">How can we help?</h2>
                            <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Possimus quam ipsa est
                                cum.
                                Accusantium maxime, odit eligendi ipsam quibusdam cupiditate!</p>
                        </li>
                        <li>
                            <h2 class="more-info">Why would I need a business COACH?</h2>
                            <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui alias voluptates
                                quia ad rerum
                                nesciunt, placeat omnis illo. Iusto perferendis perspiciatis reiciendis pariatur vitae et.
                            </p>
                        </li>
                        <li>
                            <h2 class="more-info">What is one-on-one coaching?</h2>
                            <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum saepe
                                recusandae expedita
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

<script>

export default {
    name: 'sectionInfo'
}

</script>

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
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
    }
}

.info-youtube {
    gap: 15px;

    img {
        border-radius: 5px;
    }
}

.title {
    width: 435px;
}

.more-info {
    font-size: 24px;
    font-weight: 100;
    border-bottom: 2px solid #797979;
    padding: 25px;
}

.more-info:hover {
    color: #20AD96;
    border: none;
    display: block;
    border-bottom: none;
    padding: 25px;
}

li {

    p {
        font-size: 14px;
        padding: 20px 0;
    }
}

.text {
    display: none;
}
</style>