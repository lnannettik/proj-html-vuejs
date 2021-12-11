<template>
    <div class="hero-container">
        <nav class="nav offset-md-1 offset-lg-2 col-lg-8 d-flex">

            <div class="left-side col-4">

                <span>GEN</span>

            </div>

            <ul class="right-side col-8 d-flex">
                <li>Home</li>
                <li>Services</li>
                <li>Skills</li>
                <li>Partners</li>
                <li>Blog</li>
                <li>Get in touch</li>
            </ul>

        </nav>

        <div class="hero-content offset-4 offset-md-2 offset-lg-5 offset-xl-6 col-6 col-md-5 col-lg-4 col-xl-4 col-xxl-3">
            <h1 class="titolone mb-5">Logistics that goes further.</h1>
            <h3 class="sottotitolo mb-5">For 20 years working with the most innovative in the field of transport.</h3>
            <button class="green-item btn me-3 ">GET IN TOUCH</button>
            <button class="not-green-item ">READ MORE</button>
        </div>
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


        &::before {
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
        font-weight: 500;
        color: #edf4ec;

        * {
            z-index: 1;
        }

        li {
            padding: 8px 20px;
            // z-index: 1;

        }

        .left-side {
            padding-top: 7px;

            span {
                font-size: 18px;
                font-weight: 700;
                letter-spacing: 5px;
                position: absolute;
                margin-left: 54px;


            }

            &::after {
                content: "NEX";
                font-size: 18px;
                font-weight: 700;
                letter-spacing: 5px;
                display: flex;
                position: relative;
                left: -30px;
                top: -12px;
                width: 82px;
                height: 50px;
                z-index: 4;
                border-start-start-radius: 25px;
                background-size: cover;
                background-color: rgba(4, 131, 131, 0.3);
                border-bottom-left-radius: 25px;
                align-items: center;
                padding-left: 30px;
                color: rgba(103, 220, 220, 0.938)
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

    .hero-content {
        position: absolute;
        top: 20%;


        .titolone {
            color: white;
            font-size: 4rem;
            font-weight: 900;

            @media (max-width: 768px) {  
                & {
                    font-size: 3rem;
                }
            }
                
                &::before {
                    content: "";
                    display: block;
                    position: relative;
                    width: 18rem;
                    height: 2rem;
                    z-index: 4;
                    background-size: cover;
                    background-color: rgba(4, 131, 131, 0.3);
                    padding-left: 30px;
                    top: 5rem;

                    @media (max-width: 768px) {  
                        & {
                            width: 13.4rem;
                            top: 4rem;
                        }
                    }
            
                }
        }

        .sottotitolo {
            color: #bebebe;
            font-weight: 300;

                @media (max-width: 768px) {  
                    & {
                        font-size: 1.2rem;
                }
            }
                
        }

    }


</style>