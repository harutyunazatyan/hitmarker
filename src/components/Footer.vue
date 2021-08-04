<template>
    <footer>
       <div class="flex justify-between footer_content">
           <div>
               <img src="../assets/images/hitmarker.png" alt="">
               <p class="short_info">Open an account in minutes, get full Control for much longer.</p>
           </div>
           <div>
               <p class="title">Company</p>
               <ul>
                   <li><a href="">About</a></li>
                   <li><a href="">Careers</a></li>
                   <li><a href="">Mobile</a></li>
               </ul>
           </div>
           <div>
               <p class="title">Contact</p>
               <ul>
                   <li><a href="">Help/FAQ</a></li>
                   <li><a href="">Press</a></li>
                   <li><a href="">Affiliates</a></li>
               </ul>
           </div>
           <div>
               <p class="title">More</p>
               <ul>
                   <li><a href="">Airline fees</a></li>
                   <li><a href="">Airlines</a></li>
                   <li><a href="">Low fare tips</a></li>
               </ul>
           </div>
           <div>
               <p class="title">Discover Our App</p>
               <div class="flex justify-between">
                   <div><img src="../assets/images/google-play.png" ></div>
                   <div><img src="../assets/images/app-store.png" ></div>
               </div>
               <div class="flex justify-around mt-5">
                   <button class="socialBtn"><img src="../assets/images/facebook.png" alt=""></button>
                   <button class="socialBtnInstagram"><img src="../assets/images/instagram.png" alt=""></button>
                   <button class="socialBtn"><img src="../assets/images/twitter.png" alt=""></button>
               </div>
           </div>
       </div>
        <div class="footer_bottom">
            <p>All rights reserved Hitmarker</p>
        </div>
    </footer>
</template>


<style scoped>
    footer {
        margin-top: 125px;
        padding: 40px;
    }

    .footer_content div {
        max-width: 250px;
    }

    .title {
        font-size: 24px;
        font-weight: bold;
        color: #2E2E46;
        margin-bottom: 7px;
    }

    ul li a {
        display: block;
        padding: 5px;
        color: #222831;
        text-decoration: none;
    }

    .short_info {
        color: rgba(46, 46, 70, 0.8);
        font-size: 14px;
        padding-top: 10px;
    }

    .socialBtnInstagram {
        background-color: #FF6810;
        border-radius: 50%;
        border: none;
        cursor: pointer;
        width: 50px;
        height: 50px;
        margin-left: 5px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .socialBtn {
        border: 1px solid #FF6810;
        border-radius: 50%;
        cursor: pointer;
        width: 50px;
        height: 50px;
        margin-left: 5px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .footer_bottom {
        display: flex;
        justify-content: center;
        padding-top: 15px;
        border-top: 1px solid rgba(105, 120, 131, 0.4);
        margin-top: 10px;
    }
</style>