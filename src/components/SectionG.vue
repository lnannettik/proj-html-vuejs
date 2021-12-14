<template>
    <section class="sec-G ">
        <div class="sec-container d-flex py-5 offset-2 col-8">

            <div class="left my-5 col-7">
                <div class="sopra">
                    
                    <div class="text-container element">
                        <h5 class="green-title mb-4">SEND A MESSAGE</h5>
                        <div class="title-container mb-4">
                            <span class="titolone mb-4">Get in </span><span class="tags">Touch</span>
                        </div>
                        <span class="text mb-4">Every week we publish content about what is best in the business world.</span>
                    </div>
                </div>

                <div class="sotto my-5">
                    <div class="first d-flex">
                        <input class="input-space mb-3 me-3" type="text" placeholder="Name">
                        <input class="input-space mb-3" type="text" placeholder="Email">
                    </div>
                    <div class="second d-flex">
                        <input class="input-space mb-3 me-3" type="text" placeholder="Phone">
                        <div class="more-info mb-3">
                            More info <span class="menu"><i class="fas fa-chevron-down"></i></span>
                        </div>
                        <div class="info-nascosto col-2">
                            <span>More info</span>
                            <span>More info</span>
                            <span>More info</span>
                        </div>
                        <!-- <input class="input-space mb-3" type="text" placeholder="More info"> -->
                    </div>

                    <input class="input-space message" type="text" placeholder="Message">
                </div>
                <button class="green-item btn">send</button>
            </div>

            <div class="right my-5 ms-5">

                <div class="text-div">
                    <h4 class="card-titolo mb-4">Technology</h4>
                    <h5 class="card-text mb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus. </h5>
                    <h5 class="card-text mb-5">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus. </h5>
                </div>

                <div class="contact d-flex my-3">
                    <div class="icon-container me-2"><i class="fas fa-phone"></i></div>
                    <span>+ 1 (305) 1234-5678</span>
                </div>
                <div class="contact d-flex my-3">
                    <div class="icon-container me-2"><i class="fas fa-envelope"></i></div>
                    <span>hello@example.com</span>

                </div>
                <div class="contact d-flex my-3">
                    <div class="icon-container me-2"><i class="fas fa-map-marker-alt"></i></div>
                    <span>Main Avenue, 987</span>
                </div>
                <button class="not-green-item btn">view map</button>

            </div>

        </div>

    </section>  
</template>

<script>
export default {
    name: 'Section-G',

}
</script>

<style scoped lang="scss">

@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

.sec-G {
    background-color: #eef4ed;

    .sec-container {


        .text-container {
            color: black;
            z-index: 4;
            position: relative;
            left: 0;
            
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
            
            .tags {
                color: $primary;
                font-size: 2.6rem;
                font-weight: 800;
                padding: 0 10px;
            }

        }

        .sotto {

            position: relative;

            .input-space {
                background-color: #dce2db;
                border: none;
                border-radius: 5px;
                width: 50%;
                padding: 8px 20px;
                border: none;
                font-weight: 300;
            }

            .more-info {
                background-color: #dce2db;
                border: none;
                border-radius: 5px;
                width: 50%;
                padding: 8px 20px;
                font-weight: 300;
                color: #656565;
                display: flex;
                justify-content: space-between;

                &:hover + .info-nascosto {
                    display: flex;
                }

                // span {
                //     padding: 8px 20px;

                // }

                &:hover {
                    background-color: #656565;
                    color:  #dce2db;
                    padding: 8px 20px 20px;


                }


                .menu {
                    color: #9a9a9a;
                    // position: relative;
                }
            }

            .info-nascosto {
                position: absolute;
                z-index: 2;
                flex-direction: column;
                display: none;
                margin-top: 50px;
                background-color: #dce2db;
                border: none;
                border-radius: 5px;
                width: 50%;
                padding: 8px 20px;
                font-weight: 300;
                color: #656565;
                margin-left: 21rem;
                top: 50px;
                right: 0px;
                transition: 30ms ease-in-out;

                &:hover {
                    display: flex;
                }



                    

            }

            .message {
                width: 100%;
            }
            
        }

        .right {

            .titolo {
                font-size: 1.3rem;
                font-weight: 500;
            }

            .card-text {
                font-size: 0.9rem;
                font-weight: 200;
            }

            .not-green-item {
                color: $primary;
            }

            .contact {

                align-items: center;

                .icon-container {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    width: 40px;
                    height: 40px;
                    color: $primary;
                    background-color: #05838328;
                    border-radius: 50px;
                }

                span {
                    color: $primary;
                    font-weight: 300;
                }
            }


        }





    }

}
    

</style>