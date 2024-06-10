<script>

</script>

<template>

    <footer class="footer-info">
        <section class="list-services">

            <div>
                <section>
                    <ul>
                        <li>
                            bla
                        </li>
                    </ul>
                    <ul>
                        <li>
                            bla
                        </li>
                    </ul>
                </section>

                <section>
                    <ul>
                        <li>
                            bla
                        </li>
                    </ul>
                </section>

                <section>
                    <ul>
                        <li>
                            bla
                        </li>
                    </ul>
                </section>
            </div>
            <img src="/img /dc-logo-bg.png" alt="" class="logo-bg">
        </section>
            

        <div class="footer-socials">
            <button>SIGN-UP NOW!</button>
            <ul class="social-list">
                <li>
                    <h3><strong>FOLLOW US</strong></h3>
                </li>
                <li>
                    <img src="/img /footer-facebook.png" alt="">
                </li>
                <li>
                    <img src="/img /footer-twitter.png" alt="">
                </li>
                <li>
                    <img src="/img /footer-pinterest.png" alt="">
                </li>
                <li>
                    <img src='/img /footer-youtube.png' alt="">
                </li>
                <li>
                    <img src="/img /footer-periscope.png" alt="maps">
                </li>
            </ul>
        </div>

    </footer>

</template>

<style scoped lang="scss">
    @import '/src/ComicsStyle.scss';
    .footer-socials{
        @include row-list;
        height: 100px;
        background-color: #303030;
        padding-left: 5rem;
        position: relative;
        z-index: 2;

    }
    .social-list{
        @include row-list;
        padding-right: 5rem;
    
    }
    li{
        padding: .5rem;
    }
    button{
        border-radius: 0;
        padding: .5rem;
        border: 2px solid $primary-color;
    }
    .footer-info{
        background-image: url(/img/footer-db.jpg);
        
        
    }
    .list-services{
        @include row-list;
        height: 300px;
    
    }
   .logo-bg{
        height: 500px;
        width: auto;
        padding-right: 5rem;
        overflow: hidden;
        position: relative;
        z-index: 1;
    }
    h3{
        color: $primary-color;
    }
 

</style>