<template>
    <div class="">
        <Header/>
        <section class="mt-20 container mx-auto px-40">
            <Jobs :jobs="jobs"/>
            <PromoteJob/>
            <Reviews/>
        </section>
        <Footer/>
    </div>
</template>

<script>
    import Header from '../components/Header'
    import Jobs from '../components/Jobs/Jobs'
    import PromoteJob from "../components/PromoteJob";
    import Reviews from '../components/Reviews/Reviews'
    import Footer from '../components/Footer'

    export default {
        data() {
            return {
                jobs: [
                    {
                        id: 1,
                        title: "Social Video Creator",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 2,
                        title: "Graphic Designer ",
                        image: require('../assets/images/image_2.png'),
                        company: "Thescore",
                        country: 'Canada',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 3,
                        title: "Esports Competition Coordinator",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 4,
                        title: "Social Video Creator",
                        image: require('../assets/images/image_2.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 5,
                        title: "Graphic Designer ",
                        image: require('../assets/images/image_1.png'),
                        company: "Thescore",
                        country: 'Canada',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 6,
                        title: "Esports Competition Coordinator",
                        image: require('../assets/images/image_2.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 7,
                        title: "Social Video Creator",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 8,
                        title: "Graphic Designer",
                        image: require('../assets/images/image_2.png'),
                        company: "Thescore",
                        country: 'Canada',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 9,
                        title: "Esports Competition Coordinator",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 10,
                        title: "Social Video Creator",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 11,
                        title: "Esports Competition Coordinator",
                        image: require('../assets/images/image_2.png'),
                        company: "Thescore",
                        country: 'Canada',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 12,
                        title: "Graphic Designer",
                        image: require('../assets/images/image_1.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 16,
                        title: "Social Video Creator",
                        image: require('../assets/images/image_2.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                    {
                        id: 14,
                        title: "Esports Competition Coordinator",
                        image: require('../assets/images/image_1.png'),
                        company: "Thescore",
                        country: 'Canada',
                        flag: require('../assets/images/canada.png'),
                    },
                    {
                        id: 15,
                        title: "Graphic Designer",
                        image: require('../assets/images/image_2.png'),
                        company: "pipeline.com",
                        country: 'Germany',
                        flag: require('../assets/images/germany.png'),
                    },
                ]
            }
        },
        components: {
            Header,
            Jobs,
            PromoteJob,
            Reviews,
            Footer
        }
    }
</script>

<style scoped>

</style>