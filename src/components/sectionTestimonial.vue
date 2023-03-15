<template>
    <section class="section section-bg">
        <div class="text-center">
            <h3 class="color-green">People are praising Maxcoach</h3>
            <h1 class="title">What make the love us?</h1>
        </div>
        <div class="testimonial-row gap-5">
            <div class="col-3 bg-white testimonial-card">
                <div>
                    <h2 class="title">It's a choice of quality for people with special needs</h2>
                    <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
                    <div class="d-flex gap-4">
                        <img class="testimonial-photo" src="/testimonial-avata-03.jpg" alt="">
                        <div>
                            <p class="title name">FLORENCE THEMES</p>
                            <p class="work">/ Multimedia Admin</p>
                        </div>
                    </div>

                </div>
            </div>
            <div class="col-3 bg-white testimonial-card">
                <div>
                    <h2 class="title">Hight level of efficiency teaching methods</h2>
                    <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
                    <div class="d-flex gap-4">
                        <img class="testimonial-photo" src="/testimonial-avata-02.jpg" alt="">
                        <div>
                            <p class="title name">MINA HOLLACE</p>
                            <p class="work">/ Freelencer</p>
                        </div>
                    </div>

                </div>
            </div>
            <div class="col-3 bg-white testimonial-card">
                <div>
                    <h2 class="title">It's a choice of quality for people with special needs</h2>
                    <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
                    <div class="d-flex gap-4">
                        <img class="testimonial-photo" src="/testimonial-avata-04.jpg" alt="">
                        <div>
                            <p class="title name">MADLEY PONDOR</p>
                            <p class="work">/ IT Specialist</p>
                        </div>
                    </div>

                </div>
            </div>
            <div class="col-3 bg-white testimonial-card d-none">
                <div>
                    <h2 class="title">It's a choice of quality for people with special needs</h2>
                    <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
                    <div class="d-flex gap-4">
                        <img class="testimonial-photo" src="/testimonial-avata-01.jpg" alt="">
                        <div>
                            <p class="title name">FLORENCE THEMES</p>
                            <p class="work">/ Multimedia Admin</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'sectionTestimonial'
}

</script>


<style lang="scss" scoped>
.testimonial-row {
    display: flex;
    justify-content: center;
    padding: 60px 0 150px;

    .testimonial-card {
        padding: 30px 30px 25px;
    }

    .title {
        font-size: 20px;
        line-height: 2rem;
        color: #8B88A1;
    }

    p {
        line-height: 1.8rem;
        font-size: 15px;
    }

    .testimonial-photo {
        width: 70px;
        height: 70px;
        border-radius: 50%;
        object-fit: cover;
        object-position: center;

    }

    .name {
        font-size: 15px;
    }

    .work{
        font-size: 13px;
    }
}

</style>