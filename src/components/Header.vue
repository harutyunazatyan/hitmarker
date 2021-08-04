<template>
    <header>
        <NavBar/>

        <div class="grid grid-cols-2 gap-4 mt-20">
            <div class="p-20">
                <p class="header_title">The home of gaming and esports jobs</p>
                <p class="header_sub_title pt-10">
                    With over 8,000 active listings from more than 50 countries, Hitmarker is the largest gaming and
                    esports jobs platform in the world. Find your dream career. Hire top talent. Make your mark.
                </p>
                <div class="flex mt-10 justify-around">
                    <button class="view_btn">View Jobs</button>
                    <button class="watch_btn flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                             stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                  d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"/>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                  d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                        <span class="pl-2">Watch our video</span>
                    </button>
                </div>
            </div>
            <div>
                <div class="header_image_field">
                    <img src="../assets/images/header_image.png" alt="header image">
                    <div class="cube_1"/>
                    <div class="cube_2"/>
                    <div class="cube_3"/>
                    <div class="cube_4"/>
                    <div class="cube_5"/>
                    <div class="cube_6"/>
                    <div class="cube_7"/>
                    <div class="cube_8"/>
                    <div class="cube_9"/>
                    <div class="cube_10"/>
                    <div class="cube_11"/>
                    <div class="cube_12"/>
                    <div class="cube_13"/>
                    <div class="cube_14"/>
                    <div class="cube_15"/>
                </div>
            </div>
        </div>

        <div class="grid grid-cols-1 gap-4 banner">
            <img src="../assets/images/company-banner.png" alt="">
        </div>
    </header>
</template>

<script>
    import NavBar from './NavBar'

    export default {
        components: {
            NavBar
        }
    }
</script>

<style scoped>
    header {
        height: 100vh;
        background: #19191B;
        padding: 45px 130px;
        position: relative;
        width: 100%;
    }

    .banner {
        position: absolute;
        bottom: -20px;
        width: 80%;
    }

    .banner img {
        width: 100%;
        height: 100%;
    }

    .header_title {
        font-size: 54px;
        line-height: 120%;
        letter-spacing: -0.5px;
        color: #FFFFFF;
    }

    .header_sub_title {
        font-size: 16px;
        line-height: 160%;
        letter-spacing: 0.004em;
        color: #FFFFFF;
    }

    .view_btn {
        background: #FF6810;
        box-shadow: inset 0 -6px 8px rgba(12, 65, 109, 0.08);
        border-radius: 6px;
        padding: 10px 30px;
        color: #fff;
    }

    .watch_btn {
        color: #fff;
    }

    .header_image_field {
        background-color: #fff;
        height: 451px;
        position: relative;
    }

    .header_image_field img {
        height: 451px;
        margin: auto;
    }

    .cube_1 {
        background: #32323E;
        width: 120px;
        height: 120px;
        position: absolute;
        top: 0;
        left: 0;
        cursor: pointer;
    }

    .cube_2 {
        position: absolute;
        width: 102px;
        height: 40px;
        right: 0;
        top: 0;
        background: #292929;
        cursor: pointer;
    }

    .cube_3 {
        position: absolute;
        width: 102px;
        height: 63px;
        right: 0;
        top: 40px;
        cursor: pointer;
        background: #484853;
    }

    .cube_4 {
        position: absolute;
        width: 38px;
        height: 38px;
        right: 64px;
        top: 103px;
        background: #19191B;
        cursor: pointer;
    }

    .cube_5 {
        position: absolute;
        width: 38px;
        height: 38px;
        right: 26px;
        top: 103px;
        background: #FF6810;
        cursor: pointer;
    }

    .cube_6 {
        position: absolute;
        width: 27px;
        height: 169px;
        right: -27px;
        top: 103px;
        cursor: pointer;
        background: #2B2A35;
    }

    .cube_7 {
        position: absolute;
        width: 93px;
        height: 93px;
        right: -93px;
        top: 271px;
        cursor: pointer;
        background: #303036;
    }

    .cube_8 {
        position: absolute;
        width: 54px;
        height: 54px;
        right: -54px;
        bottom: -54px;
        cursor: pointer;
        background: #303036;
    }

    .cube_9 {
        position: absolute;
        width: 89px;
        height: 88px;
        right: 109px;
        bottom: -88px;
        cursor: pointer;
        background: #FFFFFF;
    }

    .cube_10 {
        position: absolute;
        width: 38px;
        height: 38px;
        left: -58px;
        bottom: 0;
        cursor: pointer;
        background: #EFE6E8;
    }

    .cube_11 {
        position: absolute;
        width: 143px;
        height: 142px;
        left: -143px;
        bottom: 85px;
        cursor: pointer;
        background: #303036;
    }

    .cube_12 {
        position: absolute;
        width: 61px;
        height: 61px;
        left: -61px;
        top: 58px;
        cursor: pointer;
        background: #F46614;
    }

    .cube_13 {
        position: absolute;
        width: 29px;
        height: 29px;
        right: 0;
        bottom: 29px;
        cursor: pointer;
        background: #303036;
    }

    .cube_14 {
        position: absolute;
        width: 29px;
        height: 29px;
        right: 29px;
        bottom: 0;
        cursor: pointer;
        background: #303036;
    }

    .cube_15 {
        position: absolute;
        width: 29px;
        height: 29px;
        right: 58px;
        bottom: 29px;
        cursor: pointer;
        background: #F46614;
    }
</style>