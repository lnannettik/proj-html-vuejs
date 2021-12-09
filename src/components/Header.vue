<template>

    <div class="header d-flex">
        <div class="header-container offset-lg-2 col-lg-8 d-flex align-middle">
            <div class="header-left col-6">
                <i class="fas fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00
            </div>

            <div class="header-right col-6">
                <ul class="link-list">
                    <li><i class="fas fa-phone"></i> + 1 (305) 1234-5678</li>
                    <li><i class="fas fa-envelope"></i> hello@example.com</li>
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

        .header-left i {
            margin: 0px 15px 0px 0px;
        }

        .header-right {
            display: flex;
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