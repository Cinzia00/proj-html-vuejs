<template>
    <section class="section">
        <div class="container">
            <div class="p-description">
                <h3 class="color-green">Let's Dream Big Together</h3>
                <p class="description ">We are pioneers of the digital approach, using leading-edge technology to
                    simplify procedurs and apply executive coaching in the new age of digitalization.
                </p>
            </div>
            <div class="grid">
                <div v-for="el in this.info">
                    <h1>{{ el.title }}</h1>
                    <p>
                        {{ el.text }}
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

export default {
    name: 'sectionInfoMore',

    data() {
        return {
            info: [
                {
                    title: 'One to One',
                    text: 'Getting the necessary clarity about the current state to help you improve your game.'
                },
                {
                    title: 'Anywhere',
                    text: 'Access to valuable and portable program which allow you to setup and live anywhere you want.'

                },
                {
                    title: 'On Time',
                    text: 'Punctuality is our top priority because it s an essential criteria to assess a program quality.'

                },
                {
                    title: 'Online Coures',
                    text: 'Online business coaching now offers you a very powerful way to empower your business into success.'

                },
                {
                    title: 'Consulting',
                    text: 'You will get a clear sense of direction for your business, thorough assessment and faster results.'

                },
                {
                    title: 'Self Development',
                    text: 'Business Coaching often keep your focus and develop you both in a professional and personal way.'
                }

            ]
        }
    }
}

</script>


<style lang="scss" scoped>
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

.learn-more:hover {
    background-color: #343142;
    color: white;
}

</style>