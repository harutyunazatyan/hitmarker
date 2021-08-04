<template>
    <div>
        <div class="flex flex-col mb-20 items-center">
            <p class="title">Promoted Jobs</p>
            <p class="sub_title">These opportunities are shown on every page of our site and shared daily on our Twitter account.</p>
        </div>
        <div class="grid grid-cols-3 gap-4">
            <template v-if="jobs.length">
                <Job v-for="job in jobs"
                     :key="job.id"
                     :job="job"/>
            </template>
        </div>
    </div>
</template>

<script>
    import Job from './Job'

    export default {
        props: ['jobs'],
        data() {
            return {}
        },
        components: {
            Job
        }
    }
</script>

<style scoped>
    .title {
        font-size: 42px;
        color: #2E2E46;
    }
    .sub_title {
        color: rgba(45, 49, 64, 0.6);
    }
</style>



