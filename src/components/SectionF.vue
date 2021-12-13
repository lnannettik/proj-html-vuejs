<template>
    <section>
        <div class="sec-container py-5">
            <div class="stuff-container my-5 offset-2 col-8 d-flex">

                <div class="left col-6">
                    <div class="text-container element">
                        <h5 class="green-title mb-4">NEWSLETTER</h5>
                        <div class="title-container mb-4">
                            <span class="tags">Know</span><span class="titolone mb-4">First</span>
                        </div>
                        <span class="text mb-4">Every week we publish content about what is best in the business world.</span>
                    </div>
                </div>

                <div class="right col-5 d-flex">
                    <input class="my-4" type="text" placeholder="Name">
                    <input type="text" placeholder="Email">
                    <button class="green-item btn">subscribe</button>
                </div>

            </div>

        </div>
        
        
    </section>  
</template>

<script>
export default {
    name: 'SectionF',

}
</script>

<style scoped lang="scss">

@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

.sec-container {
    background-image: url(../assets/bg-1.jpg);
    background-position: center;
    background-repeat: no-repeat;
}

    .left {
        display: flex;
        align-items: center;
    }
    
    
        .text-container {
            color: white;
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
                font-size: 1rem;
                font-weight: 300;
                color: #e5ebe5;
            }

            .tags {
                color: white;
                font-size: 2.6rem;
                font-weight: 800;
                padding: 0 10px;
            }

        }

    .right {
        flex-direction: column;
    

        input {
            display: flex;
            flex-grow: 1;
            border-radius: 5px;
            padding: 8px 20px;
            background: rgba(255, 255, 255, 0.4);
            border: none;
            font-weight: 300;
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



</style>