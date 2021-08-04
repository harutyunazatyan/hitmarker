<template>
    <div class="flex flex-col mb-5">
        <p class="title">{{job.title}}</p>
        <div class="flex items-center mb-3 mt-3">
            <img :src="job.image" :alt="job.title" class="companyImage">
            <span class="company">{{job.company}}</span>
        </div>
        <div class="flex items-center">
            <img :src="job.flag" :alt="job.title" class="flag">
            <p class="country">{{job.country}}</p>
        </div>
    </div>
</template>

<script>
    export default {
        props: ['job']
    }
</script>

<style scoped>
    .title {
        font-size: 18px;
        line-height: 160%;
        letter-spacing: 0.004em;
        color: #000000;
    }

    .company {
        font-size: 16px;
        line-height: 160%;
        letter-spacing: 0.004em;
        color: #000000;
        padding-left: 7px;
    }

    .country {
        font-size: 12px;
        line-height: 160%;
        letter-spacing: 0.004em;
        color: #828282;
        padding-left: 7px;
    }

    .companyImage {
        width: 24px;
        height: 24px;
        border-radius: 50%;
    }

    .flag {
        width: 22px;
        height: 18px;
    }
</style>