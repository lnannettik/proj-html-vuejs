<template>
    <section class="section1">
        <div class="sec-container py-5 flex-column flex-xl-row offset-lg-2 col-lg-8">
            <div class="text-container my-5 col-8 col-xl-4 element">
                <h5 class="green-title mb-4">OUR BUSINESS AREAS</h5>
                <h1 class="titolone mb-4">Logistics services</h1>
                <h5 class="text mb-4">We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professional</h5>
                <span class="tags">Tradition</span>
                <span class="tags">Quality</span>
                <span class="tags">Security</span>
                <button class="green-item btn">read more</button>
            </div>

            <div class="card my-5 col-8 col-xl-4 element">
                <div class="img-container mb-4">
                    <img src="../assets/gallery-3.jpg" alt="fig">
                </div>
                <h4 class="card-titolo mb-4">Technology</h4>
                <h5 class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus. </h5>
            </div>

            <div class="card my-5 col-8 col-xl-4 element">
                <div class="img-container mb-4">
                    <img src="../assets/gallery-5.jpg" alt="fig">
                </div>
                <h4 class="card-titolo mb-4">Technology</h4>
                <h5 class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus. </h5>
            </div>
            
        </div>

    </section>

  
</template>

<script>
export default {
    name: 'SectionA',

}
</script>

<style scoped lang='scss'>

@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

    .section1 {
        background-color: #e5ebe5;
        max-width: 100vw;


        .sec-container {
            background-color: #e5ebe5;
            display: flex;
            align-items: center;

            .element {
                margin-right: 1rem;
                padding: 1rem;



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
                    font-size: 0.9rem;
                }

                .btn {
                    display: block;
                    outline: none;
                    margin-top: 25px;
                
                    &:active {
                        border-style: outset;
                    }
                }
            }

            .card {
                border-radius: 1rem;
                padding: 2.5rem 3.5rem 3rem;

                img {
                    width: 100%;
                    height: 100%;
                }

                .titolo {
                    font-size: 1.3rem;
                    font-weight: 500;
                }

                .card-text {
                    font-size: 0.9rem;
                    font-weight: 200;
                }

            }


        }
    }





</style>