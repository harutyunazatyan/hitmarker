<template>
    <div class="promoteField">
        <div>
            <p class="title">Promote Your job</p>
            <p class="sub_title">Listings that are promoted average over 200% more views and 150% more applications.</p>
        </div>
        <div>
            <button class="promoteBtn">
                <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M13 7l5 5m0 0l-5 5m5-5H6" />
                </svg>
            </button>
        </div>
    </div>
</template>

<script>

    export default {
        data() {
            return {}
        }
    }
</script>

<style scoped>
    .promoteField {
        height: 110px;
        display: flex;
        justify-content: space-between;
        padding: 24px;
        background: #FF6810;
        box-shadow: inset 0px -6px 8px rgba(12, 65, 109, 0.08), inset 0px 4px 8px rgba(8, 46, 78, 0.25);
        border-radius: 10px;
        color: #fff;
        margin-top: 74px;
    }

    .title {
        font-size: 24px;
    }

    .sub_title {
        font-size: 16px;
    }

    .promoteBtn {
        border: 1px solid #FF6810;
        border-radius: 50%;
        cursor: pointer;
        background-color: #fff;
        width: 50px;
        height: 50px;
        color: #FF6810;
    }
</style>