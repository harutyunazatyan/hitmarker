<template>
    <nav class="flex justify-between items-center">
        <div>
            <img src="../assets/images/hitmarker-logo.png" alt="">
        </div>
        <div class="nav_links">
            <a href="">Find a job</a>
            <a href="">Post a job</a>
            <a href="">Career advice</a>
        </div>
        <div>
            <button>Login</button>
            <button class="registerBtn">Create Account</button>
        </div>
    </nav>
</template>

<style scoped>
    nav {
        color: #fff;
    }

    .registerBtn {
        background: #FF6810;
        box-shadow: inset 0px -6px 8px rgba(12, 65, 109, 0.08);
        border-radius: 6px;
        padding: 10px 20px;
        margin-left: 20px;
    }

    .nav_links a {
        padding-left: 20px;
    }
</style>