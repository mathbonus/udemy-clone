<template>
    <div class="reviews">
        <div class="container">
            <h3>What our students have to say</h3>
            <!-- toDo: Add carousel -->
            <div class="row">
                <div class="col-12 col-md-4 col-sm-12 col-xl-4 col-lg-4 item">
                    <div class="reviewsItem">
                        <div class="circle"></div>
                        <div class="name">Borivoje</div>
                        <p>
                            Udemy is a life saver. I don't have the time or
                            money for a college education. My goal is to become
                            a freelance web developer, and thanks to Udemy, I'm
                            really close.
                        </p>
                    </div>
                </div>
                <div class="col-12 col-md-4 col-sm-12 col-xl-4 col-lg-4 item">
                    <div class="reviewsItem">
                        <div class="circle"></div>
                        <div class="name">Dipesh</div>
                        <p>
                            I believe in lifelong learning and Udemy is a great
                            place to learn from experts. I've learned a lot and
                            recommend it to all my friends.
                        </p>
                    </div>
                </div>
                <div class="col-12 col-md-4 col-sm-12 col-xl-4 col-lg-4 item">
                    <div class="reviewsItem">
                        <div class="circle"></div>
                        <div class="name">Kathy</div>
                        <p>
                            My children and I LOVE Udemy! The courses are
                            fantastic and the instructors are so fun and
                            knowledgeable. I only wish we found it sooner.
                        </p>
                    </div>
                </div>
            </div>
            <div class="companies">
                Trusted by companies of all sizes
            </div>
            <div class="logos">
                <div class="logoRow">
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/booking.svg"
                            alt="booking"
                        />
                    </span>
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/volkswagen.svg"
                            alt="vw"
                        />
                    </span>
                </div>
                <div class="logoRow">
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/mercedes.svg"
                            alt="mercedes"
                            width="118"
                            height="28"
                        />
                    </span>
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/pinterest.svg"
                            alt="pinterest"
                        />
                    </span>
                </div>
                <div class="logoRow">
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/adidas.svg"
                            alt="adidas"
                        />
                    </span>
                    <span class="companyLogo">
                        <img
                            src="https://i.udemycdn.com/partner-logos/paypal.svg"
                            alt="paypal"
                        />
                    </span>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.reviews {
    background-color: #f7f8fa;
}

.reviewsItem {
    box-shadow: 0 2px 2px #e0e1e4;
    padding: 30px 0;
    background-color: white;
    margin: 20px 1px;
    height: 280px;
}

h3 {
    padding-top: 20px;
    color: #29303b;
}

.circle {
    background: grey;
    width: 70px;
    height: 70px;
    border-radius: 50%;
    display: inline-block;
    margin-left: 25px;
}

.item:nth-of-type(2) .circle {
    background-color: tomato;
}

.item:nth-of-type(3) .circle {
    background-color: rgb(11, 137, 168);
}

.name {
    display: inline-block;
    position: relative;
    bottom: 25px;
    padding-left: 20px;
    font-size: 17px;
    font-weight: 500;
}

p {
    font-size: 17px;
    margin: 0 30px;
    padding-top: 10px;
    opacity: 0.9;
}

.item {
    padding: 0 5px;
}

.companies {
    text-align: center;
    margin-top: 20px;
    opacity: 0.6;
}

.companyLogo {
    margin-right: 24px;
}

.logos {
    display: table;
    margin: 0 auto;
    padding-top: 40px;
}

.logoRow {
    display: inline-block;
}

@media (max-width: 768px) {
    .logoRow {
        display: table;
        margin: 0 auto;
    }

    .reviewsItem {
        margin: 7px 1px;
        height: auto;
    }
}

@media (max-width: 992px) {
    .companyLogo {
        margin-right: 16px;
    }
}

@media (max-width: 576px) {
    .logos {
        margin: 0 auto;
    }
}
</style>
