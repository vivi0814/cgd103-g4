<template>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
    <header class="container hd">
        <div class="nav">
            <h1 class="h_logo">
                <router-link to="/" style="font-size:0;">JET SPEED
                    <svg width="108" height="40" viewBox="0 0 108 40" xmlns="http://www.w3.org/2000/svg">
                        <path d="M18.9632 0.377003L18.2846 0L17.606 0.377003L9.18002 4.95759L0.735156 9.55702L0 9.95288V10.8011V29.18V30.0283L0.735156 30.4241L17.606 39.623L18.2846 40L18.9632 39.623L35.8341 30.4241L36.5693 30.0283V29.18V10.8011V9.95288L35.8341 9.55702L18.9632 0.377003ZM10.5184 7.44581L18.2846 3.22337L33.7418 11.6494V21.0179L28.5768 18.1904L29.6136 16.3242L18.492 10.1225L18.3977 9.95288L18.2846 9.99057L18.1904 9.93402L18.115 10.0848L2.82752 18.4543V11.6305L10.5184 7.44581ZM33.7229 24.2224L33.7418 24.1847V28.3506L19.6984 36.0038L19.6418 23.2611L25.7681 26.6164L27.1254 24.1282L19.623 20.0189L19.6041 13.968L24.8445 16.8897L23.8077 18.7936L33.7229 24.2224ZM16.7766 14.0434L16.852 35.9849L2.82752 28.3318V21.6777L8.67107 18.4731V28.0867H11.4986V16.9274L16.7766 14.0434ZM47.4081 23.6569H106.032V22.1489H47.4081V23.6569ZM56.4562 16.5316V11.5928H57.9642V16.5693V16.607V16.6447C57.8511 17.8888 56.6258 19.868 53.3271 19.9058C51.4232 19.9246 50.0283 19.623 48.9915 19.0009C47.9359 18.3789 47.3704 17.4929 47.0688 16.5316L48.5014 16.0792C48.7088 16.7578 49.0858 17.3044 49.7644 17.7003C50.4618 18.115 51.574 18.3977 53.3082 18.3789C55.8153 18.36 56.3996 17.0028 56.4562 16.5316ZM85.6739 27.6155H84.9199V28.3695V31.7625V35.1555V35.9095H85.6739H94.345V34.4015H86.4279V32.5165H94.345V31.0085H86.4279V29.1235H94.345V27.6155H85.6739ZM72.4788 27.804H73.2328H82.0924V29.312H73.9868V31.2912H82.0924V32.7992H73.9868V34.7785H82.0924V36.2865H73.2328H72.4788V35.5325V32.0452V28.558V27.804ZM61.3572 10.8388H60.6032V11.5928V15.3629V19.1329V19.8869H61.3572H70.4053V18.3789H62.1112V16.1169H70.4053V14.6089H62.1112V12.3468H70.4053V10.8388H61.3572ZM76.5316 12.3468H72.6673V10.8388H77.2856H81.9039V12.3468H78.0396V20.6409H76.5316V12.3468ZM58.0396 30.4995C57.8888 29.689 57.229 28.803 55.9661 28.2375C54.7031 27.672 52.8181 27.427 50.1037 27.8228L50.0283 27.8417L49.9529 27.8605C49.5193 28.0113 49.0481 28.2375 48.6334 28.5014C48.2564 28.7465 47.7851 29.1235 47.6155 29.6513C47.5212 29.9529 47.5212 30.2922 47.672 30.5938C47.804 30.8954 48.049 31.1216 48.3129 31.3101C48.8219 31.6682 49.6324 31.951 50.7446 32.196C52.1206 32.4976 53.1574 32.6484 53.9491 32.7615C54.2319 32.7992 54.4958 32.8369 54.7031 32.8558C55.0801 32.8935 55.3629 32.9312 55.5891 32.9877C55.8907 33.0443 56.0038 33.1197 56.0792 33.1951C56.2111 33.3271 56.3431 33.5533 56.6258 34.0999C56.5881 34.1376 56.4939 34.1942 56.3431 34.2507C55.8341 34.4392 54.967 34.5523 53.9868 34.59C53.0066 34.6089 51.9887 34.5523 51.1781 34.4392C50.7823 34.3827 50.443 34.3261 50.1979 34.2507C50.0848 34.213 50.0283 34.1942 49.9717 34.1753C49.8209 34.0057 49.689 33.8737 49.5759 33.7606L49.557 33.7418C49.4251 33.6098 49.3497 33.5344 49.2743 33.4401C49.1423 33.2893 49.0104 33.0632 48.8973 32.5353L47.427 32.8558C47.5778 33.5721 47.804 34.0245 48.1244 34.4015C48.2564 34.5523 48.3883 34.6843 48.5014 34.7974L48.5391 34.8351C48.6711 34.9482 48.7842 35.0613 48.8973 35.2121C49.0481 35.4006 49.2366 35.4948 49.3685 35.5514C49.5005 35.6079 49.6701 35.6645 49.8209 35.7022C50.1414 35.7964 50.5561 35.8718 50.9896 35.9284C51.8756 36.0415 52.9689 36.1169 54.0245 36.098C55.0613 36.0792 56.1169 35.9661 56.8897 35.6645C57.2667 35.5137 57.6814 35.2875 57.9453 34.9105C58.2469 34.4581 58.2281 33.9303 58.0019 33.459C57.738 32.9312 57.4929 32.4599 57.1725 32.1395C56.7955 31.7625 56.3808 31.6117 55.9095 31.5174C55.6268 31.4609 55.2498 31.4232 54.8162 31.3666C54.6089 31.3478 54.4015 31.3101 54.1753 31.2912C53.4213 31.197 52.4411 31.0462 51.1027 30.7446C50.0471 30.5184 49.4816 30.2733 49.2177 30.0848C49.1989 30.066 49.18 30.0471 49.1612 30.0471C49.1612 30.0471 49.1612 30.0471 49.18 30.0283C49.18 30.0283 49.18 30.0283 49.1989 30.0094C49.2743 29.934 49.3685 29.8586 49.5193 29.7644C49.7832 29.5947 50.1225 29.4251 50.4618 29.2931C52.9501 28.935 54.4958 29.1989 55.4006 29.5947C56.3242 30.0094 56.5693 30.5372 56.607 30.7446L58.0396 30.4995ZM60.4147 27.9925H61.1687H68.2187H68.2375H68.2564C68.803 28.0113 69.5382 28.2564 70.1037 28.8784C70.7069 29.5193 71.0462 30.4807 70.9519 31.819V31.8379V31.8567C70.8954 32.2714 70.688 32.8746 70.2922 33.3836C69.8586 33.9114 69.1989 34.3827 68.2564 34.4204H68.2375H68.2187H61.9227V35.9095H60.4147V28.7465V27.9925ZM61.9227 32.9123H68.2187C68.6334 32.8935 68.9161 32.705 69.1046 32.4599C69.312 32.196 69.4251 31.8756 69.4628 31.6682C69.5382 30.688 69.2743 30.1791 69.0104 29.8963C68.7465 29.6136 68.4072 29.5005 68.2187 29.5005H61.9416V32.9123H61.9227ZM97.5683 27.804L96.7955 27.7851V28.558V35.5325V36.2865H97.5495H103.544H103.563H103.582C104.222 36.2677 105.184 36.0415 106.013 35.4383C106.861 34.8162 107.54 33.8172 107.559 32.328C107.578 30.8388 106.918 29.7832 106.089 29.0669C105.297 28.3883 104.336 28.049 103.676 27.9359L103.619 27.9171H103.563L97.5683 27.804ZM98.3035 34.7785V29.3308L103.468 29.4439C103.902 29.5382 104.562 29.7832 105.09 30.2356C105.617 30.688 106.032 31.3478 106.032 32.328C106.013 33.3082 105.617 33.8737 105.108 34.2319C104.581 34.6089 103.94 34.7597 103.525 34.7785H98.3035Z"/>
                    </svg>
                </router-link>
            </h1>
                <ul id="h_list" class="h_list font-16-15em" :class="toggle?'show':''">
                    <li v-for="item in items" :key="item">
                        <router-link @click="check" class="go" :to ="{path:`/${item['sourc']}`}">{{item['name']}}</router-link>
                    </li>
                </ul>
            <div class="h_feature">
                <router-link v-show="!$store.state.mem_no" to="/login"><i class="fa-regular fa-user"></i></router-link>
                <router-link v-show="$store.state.mem_no" to="/membership"><i class="fa-solid fa-list-ol"></i></router-link>
                <router-link to="/shopcart"><i class="fa-solid fa-cart-shopping"></i></router-link>
                <div v-show="$store.state.mem_no" class="logout" @click="logout"><i class="fa-solid fa-right-from-bracket"></i></div>
                <div id="hambur" class="hambur" @click="toggle=!toggle">
                    <div class="hambox"></div>
                    <div class="hambox"></div>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
import faq from "@/assets/js/faq.js"
export default {
    props: {
    },
    data(){
        return{
            items:[{name:'列車介紹', sourc:'train'},{name:'行程介紹',sourc:'travel'},{name:'消息專區',sourc:'news'},{name:'線上商城',sourc:'shop'},{name:'關於我們',sourc:'about'}],
            toggle: false,
            out:false,
        }
    },
    mounted(){
        this.see();
    },
    methods: {
        see(){
            if(this.mem_no){
                this.out = true
            }
        },
        check(){
            let h_list = document.getElementById("h_list");
            if(this.toggle == true){
                h_list.classList.remove("show");
                this.toggle = false;
            }      
        },
        logout(){
            this.$store.dispatch("setMember", null);
            location.reload();
        },
    },
    computed:{
        mem_no(){
            return this.$store.state.mem_no
            
        }
    },
}
</script>
<style lang="scss" scoped>
@import "../assets/scss/base/base.scss";
@import "../assets/scss/base/color.scss";
// *{ outline: solid 1px; }

.hd.hd-shadow{
    box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.08);
    transition: 0.5s;
}
.container {
    position: fixed;
    top: 0;
    z-index: 100;
    width: 100%;
    height: 70px;
    background-color: #fff;
    transition: 1s;
    .nav {
        display: flex;
        position: relative;
        box-sizing: border-box;
        padding: 15px 30px;
        max-width: 1260px;
        margin: auto;
        height: 70px;
        justify-content: space-between;
        align-items: center;
        a{
            color: $color_444;
            transition: 0.3s;
            &:hover{
                color: $back_color_hover;
                transition: 0.3s;
            }
            svg, i{
                fill: $color_444;
                color: $color_444;
                transition: 0.3s;
                &:hover{
                    fill: $back_color_hover;
                    color: $back_color_hover;
                    transition: 0.3s;
                }
            }
        }
        .h_list {
            transition: opacity 0.4s,left 0s 0.4s;
            opacity: 0;
            left: -100%;
            position: absolute;
            top: 100%;
            padding: 0;
            width: 100%;
            list-style: none;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            align-items: center;
            background-color: #fff;
            height: calc(100vh - 70px);
            a{
                &.router-link-exact-active{
                    padding-bottom: 5px;
                    border-bottom: 1px solid rgba($back_color_hover,0.5);
                    color: $back_color_hover;
                }
            }
        }
        .h_list.show{
            transition: opacity 0.3s,left 0s;
            height: calc(100vh - 70px);
            opacity: 1;
            left: 0px;
        }
        .h_feature {
            display: flex;
            align-items: center;
            justify-content: center;
            a+a{
                margin-left: 20px;
            }
            .logout{
                margin-left: 20px;
                cursor: pointer;
                transition: 0.3s;
                &:hover{
                    fill: $back_color_hover;
                    color: $back_color_hover;
                    transition: 0.3s;
                }
            }
            .hambur {
                cursor: pointer;
                margin-left: 20px;
                width: 18px;
                height: 25px;
                display: flex;
                flex-direction: column;
                justify-content: space-evenly;
                .hambox {
                    transition: 0.3s;
                    width: 100%;
                    height: 1.8px;
                    background-color: $color_444;
                }
                &:hover .hambox{
                    background-color: $back_color_hover;
                }
            }
        }
    }
}
    
@media screen and (min-width: 1024px) {
    .container {
        .nav{
            .h_list {
                padding: 0;
                max-width: 700px;
                list-style: none;
                display: flex;
                height: 70px;
                justify-content: space-evenly;
                align-items: center;
                position: initial;
                opacity: 1;
                flex-direction: row;
            }
            .h_feature {
                display: flex;
                align-items: center;
                justify-content: center;
                .hambur{
                    display: none;
                }
            }
        }
    }
}
</style>