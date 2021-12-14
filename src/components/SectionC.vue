<template>
    <section class="sectionC">

        <div class="sec-container d-flex offset-2 col-8">
            <div class="img-container col-6 col-md-4 col-lg-2">
                <img class="less" src="../assets/logo-5.png" alt="less">
            </div>
            <div class="img-container col-6 col-md-4 col-lg-2">
                <img class="center" src="../assets/logo-1.png" alt="less">
            </div>
            <div class="img-container col-6 col-md-4 col-lg-2">
                <img class="center" src="../assets/logo-2.png" alt="less">
            </div>
            <div class="img-container col-6 col-md-4 col-lg-2">
                <img class="center" src="../assets/logo-3.png" alt="less">
            </div>
            <div class="img-container col-6 col-md-4 col-lg-2">
                <img class="center" src="../assets/logo-4.png" alt="less">
            </div>
            <div class="img-container col-6 col-md-4 col-lg-2 less">
                <img class="less" src="../assets/logo-5.png" alt="less">
            </div>
        </div>

    
    </section>  
</template>

<script>
export default {
    name: 'Section-C',

}
</script>

<style scoped lang="scss">

    .sectionC {
        background: #eef4ed;
        color: #737373;

        .sec-container {
            flex-wrap: wrap;


            .img-container {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 200px;
                color: #737373;
    
    
                .less {
                    color: #737373;
                    width: 2.5rem;
                }
    
                .center {
                    width: 6rem;
                }
    
            }
        }

        

    }

</style>