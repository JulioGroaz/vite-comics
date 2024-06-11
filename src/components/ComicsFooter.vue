<script>

</script>

<template>

    <footer class="footer-info">
        <section class="list-services">

            <div class="list-row">
                <section >
                    <ul>
                        <li>
                            <h2>DC COMICS</h2>
                        </li>
                        <li class="list-services-style">
                            characters
                        </li>
                        <li class="list-services-style">
                            Comics 
                        </li>
                        <li class="list-services-style">
                            Movies
                        </li>
                        <li class="list-services-style">
                            TV
                        </li>
                        <li class="list-services-style">
                            Games
                        </li>
                        <li class="list-services-style">
                            Videos
                        </li>
                        <li class="list-services-style">
                            News
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h2>SHOP</h2>
                        </li>
                        <li class="list-services-style">
                            Shop DC
                        </li>
                        <li class="list-services-style">
                            Shop DC Collectibles
                        </li>
                    </ul>
                </section>

                <section>
                    <ul>
                        <li>
                            <h2>DC</h2>
                        </li>
                        <li class="list-services-style">
                            Term of Use
                        </li>
                        <li class="list-services-style">
                            Privacy Policy (New)
                        </li>
                        <li class="list-services-style">
                            Ad Choices
                        </li>
                        <li class="list-services-style">
                            Advertising
                        </li>
                        <li class="list-services-style">
                            Jobs
                        </li>
                        <li class="list-services-style">
                            Subscriptions
                        </li>
                        <li>

                        </li>
                        <li class="list-services-style">

                        </li>
                        <li class="list-services-style">

                        </li>
                        <li class="list-services-style">

                        </li>
                        <li class="list-services-style">

                        </li>
                    </ul>
                </section>

                <section>
                    <ul>
                        <li>
                            <h2>SITES</h2>
                        </li>
                        <li class="list-services-style">
                            DC
                        </li>
                        <li class="list-services-style">
                            MAD magazine
                        </li>
                        <li class="list-services-style">
                            DC Kids
                        </li>
                        <li class="list-services-style">
                            DC Universe
                        </li>
                        <li class="list-services-style">
                            DC Power Visa
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
        list-style: none;
    }
    button{
        border-radius: 0;
        padding: .5rem;
        border: 2px solid $primary-color;
        background-color: #303030;
        color: white;
        font-weight: bold;
    }
    .footer-info{
        background-image: url(/img/footer-db.jpg);
        
        
    }
    .list-services{
        @include row-list;
        height: 500px;
        background-image: url;
        background-color: #1e1e1e;
    }
   .logo-bg{
        height: 600px;
        width: auto;
        padding-right: 5rem;
        overflow: hidden;
        position: relative;
        z-index: 1;
    }
    h3{
        color: $primary-color;
    }
    .list-row{
        @include row-list;
        display: flex;
        align-items: start;
        padding-left: 5rem;
        
    }
    h2{
        color: white;

    }
    .list-services-style{
        color: #524f4f;
    }
 

</style>