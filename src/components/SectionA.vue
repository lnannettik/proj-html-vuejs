<template>
    <section class="section1">
        <div class="sec-container offset-2 col-lg-8">
            <div class="text-container col-4 element">
                <h5 class="green-title mb-4">OUR BUSINESS AREAS</h5>
                <h1 class="titolone mb-4">Logistics services</h1>
                <h5 class="text mb-4">We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professional</h5>
                <span class="tags">Tradition</span>
                <span class="tags">Quality</span>
                <span class="tags">Security</span>
                <button class="green-item btn">read more</button>
            </div>

            <div class="card col-4 element">
                <img class="mb-3" src="../assets/gallery-3.jpg" alt="fig">
                <h3 class="card-titolo">Technology</h3>
                <h5 class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus, </h5>
            </div>

            <div class="card col-4 element">
                <img class="mb-3" src="../assets/gallery-3.jpg" alt="fig">
                <h3 class="card-titolo">Technology</h3>
                <h5 class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur necessitatibus, </h5>
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

        .sec-container {
            background-color: #e5ebe5;
            display: flex;
            align-items: center;

            .element {
                width: 30%;
                margin: 10% 1%;
                padding: 3rem;

                .green-title {
                    color: #4db2b0;
                    font-weight: 500;
                    font-size: 1rem;
                }

                .titolone {
                    font-size: 3rem;
                    font-weight: 700;
                }

                .text {
                    font-size: 1rem;
                    font-weight: 200;
                }

                .btn {
                    outline: none;
                    margin-top: 25px;
                
                    &:active {
                        border-style: outset;
                    }
                }
            }

            .card {
                border-radius: 1rem;
                padding: 3rem 4rem;

                .titolo {
                    font-size: 1.6rem;
                    font-weight: 500;
                }

                .card-text {
                    font-size: 1rem;
                    font-weight: 200;
                }

            }


        }
    }





</style>