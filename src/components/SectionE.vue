<template>
    <section class="sectionE col-8 offset-2">

        <div class="section-container pb-5 d-flex">

            <div class="img-container left">
                <img src="../assets/news-1.jpg" alt="">
                <div class="contenuto">
                    <span class="titolo">Lorem ipsum dolor sit amet consectetur.</span>
                </div>
            </div>

            <div class="img-container cnt">
                <img src="../assets/news-2.jpg" alt="">
                <div class="contenuto">
                    <span class="titolo">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum?</span>
                </div>

            </div>

            <div class="img-container right">
                <img src="../assets/news-3.jpg" alt="">
                <div class="contenuto">
                    <span class="titolo">Lorem ipsum dolor sit amet consectetur adipisicing.</span>
                </div>

            </div>

        </div>
    
    </section>  
</template>

<script>
export default {
    name: 'Section-E',

}
</script>

<style scoped lang="scss">

    .section-container {
        justify-content: space-between;
        width: 100%;
        padding-top: 20px;
        

        .img-container {
            width: 31%;
            border-radius: 1rem;
            position: relative;

            img {
                border-radius: 1rem;
                width: 100%;
                height: 100%;
            }

            .contenuto {
                height: 100%;
                width: 100%;
                background: rgba(0, 0, 0, 0.4);   
                position: absolute;
                padding: 2rem;
                left: 0;
                top: 0;
                border-radius: 1rem;
                color: white;
                display: flex;
                align-items: end;

                @media (max-width: 1200px) {  
                    & {
                        padding: 1rem;
                    }
                }

            }

            span {
                font-size: 1.4rem;
                font-weight: 700;
                text-align: center;


                @media (max-width: 1200px) {  
                    & {
                        font-size: 1rem;
                        font-weight: 500;
                    }
                }

                @media (max-width: 992px) {  
                    & {
                        font-size: 0.8rem;
                        font-weight: 500;
                    }
                }

            }

        }
    }

</style>