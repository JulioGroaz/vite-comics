<script>

</script>

<template>

<header class="header-container">
    <img src="/img /dc-logo.png" alt="">
    <ul class="header-list">
        <li>
            CHARACTERS
        </li>
        <li>
            COMICS
        </li>
        <li>
            MOVIES
        </li>
        <li>
            TV
        </li>
        <li>
            GAMES
        </li>
        <li>
            COLLECTIBLES
        </li>
        <li>
            VIDEOS
        </li>
        <li>
            FANS
        </li>
        <li>
            NEWS
        </li>
        <li>
            SHOP
        </li>
    </ul>
</header>

</template>

<style scoped lang="scss">
@import '/src/ComicsStyle.scss';
    .header-container{
        @include row-list;
        width: 100%;
        height: 200px;
        padding-right: 5rem;
        padding-left: 5rem;

    }
    .header-list{
        @include row-list;
    }
    li{
        padding: 1rem;
    }

</style>