<template>
<section class="sec-H">
    <div class="section-container py-5 d-flex">
        <div class="content my-5 p-5 d-flex offset-2 col-8">
            <div class="first cards">

                <div class="left-side col-4">

                    <span>GEN</span>

                </div>

                <div class="text-div">
                    <h5 class="text">A Functional HTML Template for Corporate and Business. </h5>
                </div>

                <div class="contact d-flex">
                    <div class="icon-container me-2"><i class="fas fa-phone"></i></div>
                    <span>+ 1 (305) 1234-5678</span>
                </div>
                <div class="contact d-flex">
                    <div class="icon-container me-2"><i class="fas fa-envelope"></i></div>
                    <span>hello@example.com</span>

                </div>
                <div class="contact d-flex">
                    <div class="icon-container me-2"><i class="fas fa-map-marker-alt"></i></div>
                    <span>Main Avenue, 987</span>
                </div>
                <button class="not-green-item btn">view map</button>

            </div>

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



        .first {
            color: white;

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
                padding: 0px 25px;
                line-height: 1;
            }

            .contact {

                align-items: center;

                .icon-container {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: white;
                }

                span {
                    color: white;
                    font-weight: 300;
                    font-size: 0,9rem;
                }
            }
        }

        .cont {
            background-color: rgba(250, 250, 250, 0.3);
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
                }
                
            }

        }

        .cards {
            width: 25%;
            display: flex;
            flex-wrap: wrap;
        }






    }
}



</style>