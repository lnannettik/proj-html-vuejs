<template>
<section class="sec-H">
    <div class="section-container py-5 d-flex">

        <div class="card-container col-8 col-md-6 offset-2 offset-md-3 offset-lg-2 col-xl-8">

            <div class="content my-5 p-5 flex-column flex-xl-row d-flex">

                <div class="single-card-container flex-column flex-xl-row p-3 p-xl-0 ">
                    <div class="first cards">

                        <div id="logo" class="left-side mb-4 col-4">
                            <span>GEN</span>
                        </div>

                        <div class="text-div mb-4">
                            <h5 class="text">A Functional HTML Template for Corporate and Business. </h5>
                        </div>

                        <div class="contact mb-4 mb-xl-1 d-flex">
                            <div class="icon-container me-2"><i class="fas fa-phone"></i></div>
                            <span>+ 1 (305) 1234-5678</span>
                        </div>

                        <div class="contact mb-4 mb-xl-1 d-flex">
                            <div class="icon-container me-2"><i class="fas fa-envelope"></i></div>
                            <span>hello@example.com</span>
                        </div>

                        <div class="contact mb-4 mb-xl-1 d-flex">
                            <div class="icon-container me-2"><i class="fas fa-map-marker-alt"></i></div>
                            <span>Main Avenue, 987</span>
                        </div>

                        <button id="last" class="not-green-item btn">view map</button>

                    </div>
                </div>

                <div class="single-card-container my-4">
                    <div class="second cards cont">
                        <div class="titolo my-3">About</div>
                        <ul class="list">
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                        </ul>
                    </div>
                </div>

                <div class="single-card-container  my-4">
                    <div class="third cards cont">
                        <div class="titolo my-3">About</div>
                        <ul class="list">
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                        </ul>
                    </div>
                </div>
                
                <div class="single-card-container my-4">
                    <div class="fourth cards cont">
                        <div class="titolo my-3">About</div>
                        <ul class="list">
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                            <li><i class="fas fa-chevron-right"></i> The Company</li>
                        </ul>
                    </div>
                </div>

                <div class="container-btn">
                    <a href="#home"><i class="fas fa-chevron-up"></i></a>
                </div>
            </div>
        </div>

    </div>
    
</section>  
</template>

<script>
export default {
    name: 'Section-H',

}
</script>

<style scoped lang="scss">


@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

.sec-H {
    background-image: url(../assets/bg-10.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;


    .section-container {
        position: relative;


        .first {
            color: $footer;
            display: flex;
            flex-direction: column;
            align-items: center;

            .text-div {
                text-align: center;
            }

            #last {
                padding: 12px 20px;
                line-height: 0.8rem;
                height: fit-content;            
            }

            .left-side {
                padding-top: 7px;

                span {
                    font-size: 18px;
                    font-weight: 700;
                    letter-spacing: 5px;
                    position: absolute;
                    margin-left: 54px;
                    color: white;
                }

                &::after {
                    content: "NEX";
                    font-size: 18px;
                    font-weight: 700;
                    letter-spacing: 5px;
                    display: flex;
                    position: relative;
                    left: -30px;
                    top: -12px;
                    width: 82px;
                    height: 50px;
                    z-index: 4;
                    border-start-start-radius: 25px;
                    background-size: cover;
                    background-color: rgba(4, 131, 131, 0.3);
                    border-bottom-left-radius: 25px;
                    align-items: center;
                    padding-left: 30px;
                    color: rgba(103, 220, 220, 0.938)
                }
            }

            .text {
                font-size: 0.9rem;
                font-weight: 200;
            }

            .not-green-item {
                color: white;

            }

            .contact {

                align-items: center;
                height: 1rem;


                .icon-container {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: $footer;
                }

                span {
                    color: $footer;
                    font-weight: 300;
                    font-size: 0,9rem;
                }
            }
        }

        // .card-container {
            
        // }

        .cont {
            background-color: rgba(250, 250, 250, 0.05);
            border-radius: 1rem;
            padding: 2.5rem;
            margin: 1rem;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;

            .titolo {
                font-size: 1.3rem;
                font-weight: 500;
                color: white;

            }

            ul {
                list-style: none;
                padding-left: 0;
                font-size: 1rem;
                font-weight: 200;
                color: white;

                li {
                    margin-bottom: 4px;
                    color: $footer;
                }
                
            }

        }

        .cards {
            // width: 25%;
            display: flex;
            flex-wrap: wrap;
        }

        .container-btn {
            width: 40px;
            height: 40px;
            background-color: white;
            border-radius: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
            // position: fixed;
            position: absolute;
            bottom: 10px;
            right: 80px;

            a {
                color: black;
            }
        }

    }
}



</style>