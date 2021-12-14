<template>

    <div id="home" class="header d-flex">
        <div class="header-container col-md-8 d-flex align-middle">
            <div class="header-left">
                <i class="fas fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00
            </div>

            <div class="header-right">
                <ul class="link-list">
                    <li><i class="fas fa-phone"></i> <span class="d-none d-xxl-inline-block">+ 1 (305) 1234-5678</span></li>
                    <li><i class="fas fa-envelope"></i> <span class="d-none d-xxl-inline-block">hello@example.com</span></li>
                    <li><i class="fab fa-facebook-f"></i></li>
                    <li><i class="fab fa-twitter"></i></li>
                    <li><i class="fab fa-linkedin-in"></i></li>
                </ul>
                
            </div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'Header',

}
</script>

<style scoped lang="scss">
@import '@/styles/utilities.scss';
@import '@/styles/variables.scss';

    .header {
        background-color: $header;
        color: #edf4ec;
        height: 3rem;
        align-items: center;
        font-size: 14px;
        font-weight: 300;
        justify-content: center;
        max-width: 100vw;

        .header-container {
            justify-content: space-between;
        }

        .header-left {
            min-width: fit-content;
        }

        .header-left i {
            margin: 0px 15px 0px 0px;
        }

        .header-right {
            display: flex;
            justify-content: flex-end;
        }

        .link-list {
            list-style: none;
            display: flex;
            align-items: center;
            margin-bottom: 0px;
            
            li {
                margin: 0px 15px;
            }
        }

    }

</style>