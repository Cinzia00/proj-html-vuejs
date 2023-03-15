<template>
    <section class="section">
        <div class="container">
            <div class="row p-description">
                <h3 class="color-green">Wanna transform your life?</h3>
                <h1 class="title">Upcoming Events</h1>
            </div>
            <div class="d-flex justify-content-center row-gap mt-5">
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> Texas, US</p>
                        <h2 class="sub-title">Storytelling Workshop</h2>
                    </div>
                    <div class="date">
                        <p class="day">22</p>
                        <p>NOV</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> New York, US</p>
                        <h2 class="sub-title">Painting Art Contest 2020</h2>
                    </div>
                    <div class="date">
                        <p class="day">10</p>
                        <p>OCT</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
            </div>
            <div class="d-flex justify-content-center mt-5 row-gap">
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> Hamburg, Germany</p>
                        <h2 class="sub-title">International Art Fair 2020</h2>
                    </div>
                    <div class="date">
                        <p class="day">23</p>
                        <p>NOV</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> Illinois, US</p>
                        <h2 class="sub-title">Street Performance: Call for Artist</h2>
                    </div>
                    <div class="date">
                        <p class="day">15</p>
                        <p>DEC</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
            </div>
            <div class="d-flex justify-content-center row-gap mt-5">
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> Illions, US</p>
                        <h2 class="sub-title">Consumer Food Safety Education Conference</h2>
                    </div>
                    <div class="date">
                        <p class="day">22</p>
                        <p>JUL</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
                <div class="d-flex bg-color">
                    <div>
                        <p class="luogo"><i class="fa-solid fa-location-dot"></i> Dubai</p>
                        <h2 class="sub-title">How meditation improve your mental health?</h2>
                    </div>
                    <div class="date">
                        <p class="day">12</p>
                        <p>AUG</p>
                        <button class="button-get-started">Get ticket</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="info d-flex justify-content-center">Excited about our event?
            <a class="text-green" href=""> View all events <i class="fa-solid fa-arrow-right-long"></i></a>
        </div>
    </section>
</template>

<script>
export default {
    name: 'sectionUpcoming'
}

</script>


<style lang="scss" scoped>
.p-description {
    text-align: center;
}

.row-gap {
    gap: 34px;
}

.bg-color {
    width: 570px;
    display: flex;
    justify-content: space-between;
    background-color: #F8F8F8;
    padding: 35px;
    border-radius: 8px;


    .sub-title {
        font-size: 1.1rem;
        font-weight: bold;
    }


    .luogo {
        font-size: 0.9rem;
        color: #797979;
    }

    .date {
        line-height: 25px;
        text-align: center;
    }

    .day {
        font-size: 2.5rem;
        color: #20AD96;
        font-weight: 100;
    }

    .button-get-started {
        width: 130px;
        padding: 5px 15px;
    }
}

    .info{
       margin-top: 50px;
       margin-bottom: 120px;
       color: #343142;

       .text-green {
        color: #20AD96;
       }
    }
</style>