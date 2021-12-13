<template>
    <section class="sectionB">

        <div class="background-container">
            <!-- <div class="space col-6"></div> -->
            <div class="img-container offset-6 col-6">
                <img src="../assets/about-5.jpg" alt="fig">
            </div>
        </div>

        <div class="another-div py-5">
    
            <div class="text-container offset-2 col-8 col-lg-4 p-5">
                <div class="come-sopra mb-5">
                    <h5 class="green-title mb-4">ABOUT THE NETWORK</h5>
                    <h1 class="titolone mb-4">The Company</h1>
                    <h5 class="text mb-4">With all this experience and capability, comes an unrivalled commitment to customers service.</h5>
                </div>
                <div class="circle-container d-flex mb-5">
                    <div class="circle">
                        <span class="number">0</span><span>%</span>
                    </div>
                    <div class="side-div">
                        <div class="title">Leadership</div>
                        <div class="subtitle">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</div>
                    </div>
                </div>
                
                <div class="circle-container d-flex mb-5">
                    <div class="circle">
                        <span class="number">0</span><span>%</span>
                    </div>
                    <div class="side-div">
                        <div class="title">Psycology</div>
                        <div class="subtitle">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</div>
                    </div>
                </div>
                
                <div class="circle-container d-flex mb-5">
                    <div class="circle">
                        <span class="number">0</span><span>%</span>
                    </div>
                    <div class="side-div">
                        <div class="title">Flexibility</div>
                        <div class="subtitle">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</div>
                    </div>
                </div>
            </div>

        </div>


    </section>  
</template>

<script>
export default {
    name: 'Section-B',

}
</script>

<style scoped lang="scss">
@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';



    .sectionB {
        max-width: 100vw;
        background-color: black;
        z-index: 0;

        .background-container {
            display: flex;
            position: absolute;
            width: 100%;

            .space {
                background-color: transparent;
                width: 50%;
            }

            .img-container {
                width: 50%;
                height: 100%;
                
                img {
                    width: 100%;
                    height: 100%;
                }
            }
        }
                
        .text-container {
            color: white;
            z-index: 4;
            position: relative;
            left: 0;
            background: rgba(0, 0, 0, 0.7);
            
            .green-title {
                color: #4db2b0;
                font-weight: 600;
                font-size: 0.8rem;
            }

            .titolone {
                font-size: 2.6rem;
                font-weight: 800;
            }

            .text {
                font-size: 0.9rem;
                font-weight: 200;
            }

            .circle-container {
                    min-width: 90px;
                    min-height: 90px;




                .circle {
                    min-width: 90px;
                    min-height: 90px;
                    border-radius: 50px;
                    border: 10px solid $primary;
                    margin-right: 2rem;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                }

                .number {
                    font-size: 1.8rem;
                    font-weight: 700;
                }

                .side-div {
                    display: flex;
                    flex-direction: column;
                    justify-content: space-between;

                        .title {
                        font-size: 1.3rem;
                        font-weight: 500;
                        }

                        .subtitle {
                            font-size: 0.9rem;
                            font-weight: 200;
                        }
                }
                
            }
        }

    }



</style>