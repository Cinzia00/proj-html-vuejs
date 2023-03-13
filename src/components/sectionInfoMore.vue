<template>
    <section class="section">
        <div class="container">
            <div class="row p-description">
                <div class="col-10">
                    <h3 class="color-green">Let's Dream Big Together</h3>
                    <p class="description">We are pioneers of the digital approach, using leading-edge technology to
                        simplify procedurs and apply executive coaching in the new age of digitalization.
                    </p>
                </div>
            </div>
            <div class="grid">
                <div>
                    <div class="d-flex">
                        <div>
                            <i class="fa-regular fa-lightbulb"></i>
                        </div>
                        <div>
                            <h1>One to One</h1>
                            <p>
                                Getting the necessary clarity about the current state to help you improve your game.
                            </p>

                        </div>
                    </div>
                </div>
                <div class="d-flex">
                    <div>
                        <img src="/add.svg" alt="">
                        
                    </div>
                    <div>
                        <h1>Anywhere</h1>
                        <p>
                            Access to valuable and portable program which allow you to setup and live anywhere you want.
                        </p>
                    </div>
                </div>
                <div>
                    <h1>On Time</h1>
                    <p>
                        Punctuality is our top priority because it's an essential criteria to assess a program quality.
                    </p>
                </div>
                <div>
                    <h1>Online Coures</h1>
                    <p>
                        Online business coaching now offers you a very powerful way to empower your business into success.
                    </p>
                </div>
                <div>
                    <h1>Consulting</h1>
                    <p>
                        You will get a clear sense of direction for your business, thorough assessment and faster results.
                    </p>
                </div>
                <div>
                    <h1>Self Development</h1>
                    <p>
                        Business Coaching often keep your focus and develop you both in a professional and personal way.
                    </p>
                </div>
            </div>
            <div class="buttons">
                <button class="learn-more">Learn more</button>
                <button class="button-get-started">Get started today</button>
            </div>
        </div>
    </section>
</template>


<script>

</script>


<style lang="scss" scoped>
.p-description {
    text-align: center;
}

.description {
    font-size: 35px;
    font-weight: bold;
    padding-bottom: 50px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(3, 3fr);
    gap: 25px;

    h1 {
        font-size: 25px;
        margin-bottom: 16px;
    }
}

.color-green {
    padding-bottom: 25px;
}

.buttons {
    text-align: center;
    margin: 60px 25px 60px;
}

.learn-more {
    width: 200px;
    background-color: white;
    color: #20AD96;
    border: 2px solid #eceeef;
    border-radius: 5px;
    padding: 15px;
    font-size: 14px;
    font-weight: bold;
    margin: 0 30px;

}
</style>