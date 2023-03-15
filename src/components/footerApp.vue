<template>
    <section class="section">
        <div class="container d-flex flex-column gap-3 text-center">
            <h2>Subscibe
                <span class="newsletter">Newsletters</span>
            </h2>
            <p>Enter your email address to to register to our newsletter subscription delivered on a regular basis!</p>
            <div>

                <div class="input-group  input">
                    <input type="text" class="form-control" placeholder="Enter your email" aria-label="Recipient's username"
                        aria-describedby="basic-addon2">
                    <span class="input-group-text input-button" id="basic-addon2">Subscribe</span>
                </div>
            </div>
            <div class="bg-image">
                <div class="position-rel">
                    <img class="position-ab img-circle" src="/maxcoach-shape-02.png" alt="">
                    <img class="position-ab" src="/maxcoach-shape-09.png" alt="">
                </div>
            </div>
        </div>
    </section>

    <section class="section-footer-bg">
        <div class="container">
            <div class="row">
                <div class="col">
                    <p class="info">Address</p>
                    <div>
                        <p>382 NE 191st St # 87394 Miami, FL 33179-3899</p>
                        <p>+1(305) 547-9909 (9am 5 pm EST, Monday - Friday)</p>
                        <p>support@maxcoach.com</p>
                        <div class="social-icon d-flex gap-4">
                            <i class="fa-brands fa-facebook fb"></i>
                            <i class="fa-brands fa-twitter"></i>
                            <i class="fa-brands fa-instagram"></i>
                            <i class="fa-brands fa-linkedin"></i>
                        </div>
                    </div>
                </div>
                <div class="col d-flex gap-5">
                    <ul>
                        <li class="info">Explore</li>
                        <li>Start here</li>
                        <li>Blog</li>
                        <li>About us</li>
                    </ul>
                    <ul class="mt-5">
                        <li>Success story</li>
                        <li>Courses</li>
                        <li>Contact us</li>

                    </ul>
                    <ul>
                        <li class="info">Information</li>
                        <li>Membership</li>
                        <li>Purchase guide</li>
                        <li>Privacy policy</li>
                        <li>Terms of service</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="text-center py-5 copyright"><i class="fa-regular fa-copyright"></i> 2020 Maxcoach. All Rights Reserved
        </div>
    </section>
</template>

<script>
export default {
    name: 'footerApp'
}
</script>



<style lang="scss" scoped>
.section {
    padding-bottom: 100px;

    .container {
        position: relative;

    }

    .bg-image {
        position: absolute;
        right: 50px;
        bottom: 50px;
        width: 200px;
        height: 200px;
    }

    .position-rel {
        position: relative;
    }

    .position-ab {
        position: absolute;
        top: 0;
        left: 0;
    }

    .img-circle {
        top: 100px;
        left: 68px;
    }
}

.newsletter {
    color: #20AD96;
}

.button-get-started {
    padding: 5px;
}

.input {
    width: 600px;
    padding: 20px;
    margin: 0 auto;

    .input-button {
        font-size: 13px;
        background-color: #20AD96;
        color: white;
    }
}

li {
    line-height: 40px;
}

.section-footer-bg {
    background-color: #171621;
    color: #bcbcbc;
    padding: 70px 0 30px;
    font-size: 15px;


    .info {
        color: white;
        font-weight: bold;
    }

    .copyright {
        font-size: 13px;
    }
}

.social-icon {
    font-size: 25px;

}
</style>