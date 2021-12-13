<template>

    <div class="section-container py-5 offset-2 col-8 d-flex">
        <div class="left pt-5 col-6">
            <div class="text-container element">
                <h5 class="green-title mb-4">OUR EDITORIAL CONTENT</h5>
                <div class="title-container mb-4">
                    <span class="titolone mb-4">Latest </span><span class="tags">News</span>
                </div>
                <span class="text mb-4">Every week we publish content about what is best in the business world.</span>
            </div>
        </div>
            
        <div class="right pt-5 col-6">
            <button class="green-item btn">see all</button>
        </div>
        
    </div>

  
</template>

<script>
export default {
    name: 'Section-D',

}
</script>

<style scoped lang="scss">

@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

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

    .right {
        display: flex;
        justify-content: flex-end;
        align-items: end;
    }

</style>