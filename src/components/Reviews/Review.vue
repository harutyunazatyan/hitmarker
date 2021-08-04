<template>
    <div class="reviewField">
        <div class="grid grid-cols-3 gap-4">
            <div class="imageField relative">
                <img src="../../assets/images/review_image.png" alt="" class="absolute z-10">
                <div class="cube">
                    <img src="../../assets/images/quote.png" alt="">
                    <img src="../../assets/images/quote.png" alt="">
                </div>
            </div>
            <div class="col-span-2">
                <div class="flex justify-around mt-20">
                    <div>
                        <p class="title">What pepole say</p>
                    </div>
                    <div class="flex">
                        <button class="prev">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                                 stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                      d="M10 19l-7-7m0 0l7-7m-7 7h18"/>
                            </svg>
                        </button>
                        <button class="next">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20"
                                 fill="currentColor">
                                <path fill-rule="evenodd"
                                      d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                      clip-rule="evenodd"/>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="reviewBox">
                    <div class="flex justify-between">
                        <div>
                            <p class="name">Darrell Steward</p>
                            <p class="profession">CEO, ESport.</p>
                        </div>
                        <div class="flex starBox">
                            <img src="../../assets/images/star-fill.png" alt="">
                            <img src="../../assets/images/star-fill.png" alt="">
                            <img src="../../assets/images/star-fill.png" alt="">
                            <img src="../../assets/images/star-fill.png" alt="">
                            <img src="../../assets/images/star.png" alt="">
                        </div>
                    </div>
                    <div>
                        <p class="review">
                            Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece
                            of classical Latin literature from 45 BC, making it over 2000 years old. Contrary to popular
                            belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin
                            literature from 45 BC, making it over 2000 years old.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        },
    }
</script>

<style scoped>
    .imageField img {
        width: auto;
        height: 100%;
        object-fit: contain;
    }

    .imageField {
        background-color: #19191B;
        position: relative;
    }

    .reviewField {
        height: 378px;
    }

    .title {
        color: #2E2E46;
        font-weight: 500;
        font-size: 42px;
    }

    .reviewBox {
        border-left: 8px solid #FF6810;
        padding: 20px;
        margin-left: -60px;
        z-index: 100;
        position: relative;
        max-width: 100%;
        margin-top: 30px;
        background: #fff;
    }

    .starBox img {
        width: 20px;
        height: 20px;
    }

    .name {
        font-size: 28px;
        color: #2E2E46;
    }

    .profession {
        font-size: 24px;
        color: #2E2E46;
    }

    .review {
        font-size: 14px;
        color: rgba(34, 40, 49, 0.9);
        padding-top: 10px;
    }

    .next {
        background-color: #FF6810;
        color: #fff;
        border: 1px solid #FF6810;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        margin: 2px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .prev {
        background-color: #fff;
        border: 1px solid #FF6810;
        color: #FF6810;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        margin: 2px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .cube {
        width: 60px;
        height: 60px;
        position: absolute;
        top: -30px;
        right: 30px;
        background-color: #FF6810;
        cursor: pointer;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .cube img {
        width: 45%;
        height: 45%;
    }
</style>