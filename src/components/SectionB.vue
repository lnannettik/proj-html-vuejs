<template>
    <section class="sectionB d-flex">
            <div class="left-side col-6">
                <div class="text-container offset-4 col-8 pe-5 my-5">
                    <div class="come-sopra mb-5">
                        <h5 class="green-title mb-4">ABOUT THE NETWORK</h5>
                        <h1 class="titolone mb-4">The Company</h1>
                        <h5 class="text mb-4">With all this experience and capability comes an unrivalled commitment to customers service.</h5>
                    </div>
                    <div class="circle-container d-flex mb-5">
                        <div class="circle">evv</div>
                        <div class="side-div">
                            <div class="title">Leadership</div>
                            <div class="subtitle">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</div>
                        </div>
                    </div>
                    
                    <div class="circle-container d-flex mb-5">
                        <div class="circle">evv</div>
                        <div class="side-div">
                            <div class="title">Psycology</div>
                            <div class="subtitle">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
                        </div>
                    </div>
                    
                    <div class="circle-container d-flex mb-5">
                        <div class="circle">evv</div>
                        <div class="side-div">
                            <div class="title">Flexibility</div>
                            <div class="subtitle">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="right-side col-6"></div>
    </section>  
</template>

<script>
export default {
    name: 'Section-B',

}
</script>

<style scoped lang="scss">

    .sectionB {
        max-width: 100vw;

        .left-side {
            background-color: black;

            .text-container {
                color: white;
                
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

                    .circle {
                        width: 5rem;
                        height: 5rem;
                        background-color: red;
                        border-radius: 50px;
                        border: 10px solid green;
                        margin-right: 2rem;
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

        .right-side {
            background-image: url(../assets/about-5.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
        }
    }



</style>