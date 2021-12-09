<template>
    <div class="hero-container">
        <nav class="nav offset-lg-2 col-lg-8 d-flex">

            <div class="left-side col-5">

                <span>NEXTGEN</span>

            </div>

            <ul class="right-side col-7 d-flex">
                <li>Home</li>
                <li>Services</li>
                <li>Skills</li>
                <li>Partners</li>
                <li>Blog</li>
                <li>Get in touch</li>
            </ul>

        </nav>
    </div>
  
</template>

<script>
export default {
    name: 'Hero',

}
</script>

<style scoped lang="scss">
@import '@/styles/utilities.scss';

    .hero-container {
        background-image: url(../assets/jumbo.jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        height: 100vh;
        position: relative;

        &::after {
            content: ' ';
            display: block;
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            background-size: cover;
            background-color: rgba(0, 0, 0, 0.5);
        }

    }

    nav {
        height: 50px;
        padding: 20px;
        font-weight: 700;
        color: #edf4ec;

        * {
            z-index: 2;
        }

        li {
            padding: 8px 20px;
            // z-index: 1;

        }

        .left-side {
            padding-top: 7px;

            span {
                font-size: 18px;
                letter-spacing: 5px;
                position: absolute;

            }

            &::after {
                content: " ";
                display: block;
                position: relative;
                left: -29px;
                top: -12px;
                width: 98px;
                height: 50px;
                z-index: 4;
                border-start-start-radius: 20px;
                background-size: cover;
                background-color: rgba(4, 131, 131, 0.3);
                border-bottom-left-radius: 20px;
            }
        }


    }

    .right-side {
        justify-content: flex-end;
        list-style: none;
        text-transform: uppercase;

        li:hover {
            background-color: #048383;
            color: white;
            width: fit-content;
            border-radius: 5px;
            padding: 8px 20px;
            text-transform: uppercase;

        }

    
    }


</style>