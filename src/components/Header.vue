<template>
    <header>
        <div class="header-wrapper__panel">
            <div class="header-panel__left">

                <div class="header-logotype"></div>

                <div class="header-notification">
                    <a class="user-messenger" href="#">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="17" viewBox="0 0 18 17">
                            <path fill="#aab6c2" fill-rule="evenodd" d="M18,10.2304688 L18,11.6015625 C18,11.9062515 17.9414068,12.210936 17.8242188,12.515625 C17.4492169,13.3359416 16.8046921,13.769531 15.890625,13.8164062 L14.9765625,13.8164062 L14.9765625,15.890625 C14.9531249,16.0078131 14.8945317,16.1015621 14.8007812,16.171875 C14.7773436,16.171875 14.7421877,16.1835936 14.6953125,16.2070312 C14.601562,16.1835936 14.5312502,16.1484377 14.484375,16.1015625 L12.1640625,13.8164062 L10.4414062,13.8164062 C10.1367172,13.7929686 9.84375141,13.7109382 9.5625,13.5703125 C8.76562102,13.1484354 8.3671875,12.492192 8.3671875,11.6015625 L8.40234375,10.2304688 C8.40234375,10.1132807 8.42578102,9.90234527 8.47265625,9.59765625 L10.7929688,9.59765625 C12.0820377,9.59765625 13.1601519,9.10547367 14.0273438,8.12109375 L15.890625,8.12109375 C16.1718764,8.12109375 16.4531236,8.16796828 16.734375,8.26171875 C17.5781292,8.61328301 18,9.26952645 18,10.2304688 Z M14.3789062,5.6953125 C14.3789062,6.32812816 14.1679709,6.92577844 13.7460938,7.48828125 C13.0195276,8.49609879 12.0351625,9 10.7929688,9 L7.59375,9 L4.7109375,12.1992188 C4.64062465,12.2695316 4.57031285,12.3046875 4.5,12.3046875 C4.47656238,12.3046875 4.44140648,12.2929689 4.39453125,12.2695313 C4.27734316,12.222656 4.20703137,12.128907 4.18359375,11.9882813 L4.18359375,9 L3.3046875,9 C2.71874707,9 2.16797133,8.88281367 1.65234375,8.6484375 C0.550775742,8.1093723 0,7.23047484 0,6.01171875 L0,3.3046875 C0,2.67187184 0.152342227,2.09765883 0.45703125,1.58203125 C1.08984691,0.527338477 2.03905617,0 3.3046875,0 L10.7929688,0 C11.4960973,0 12.1640593,0.199216758 12.796875,0.59765625 C13.8515678,1.27734715 14.3789062,2.17968188 14.3789062,3.3046875 L14.3789062,5.6953125 Z"></path>
                        </svg>
                    </a>
                    <a clas="user-friend" href="#">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="17" viewBox="0 0 18 17">
                            <path fill="#aab6c2" fill-rule="evenodd" d="M17.2265625,14.484375 C17.7187525,15.5390678 17.9765624,16.6054634 18,17.6835938 C17.9765624,17.8476571 17.8710947,17.9531248 17.6835938,18 L0.31640625,18 C0.15234293,17.9765624 0.0468752344,17.8710947 0,17.6835938 C0,16.6054634 0.257809922,15.5390678 0.7734375,14.484375 C0.890625586,14.2734364 1.07812371,14.0625011 1.3359375,13.8515625 C1.85156508,13.4062478 3.24608238,12.7500043 5.51953125,11.8828125 C5.61328172,11.8593749 5.97655934,11.7304699 6.609375,11.4960938 L6.609375,9.421875 C6.04687219,8.90624742 5.74218773,8.19141082 5.6953125,7.27734375 C5.50781156,7.11328043 5.3789066,6.86718914 5.30859375,6.5390625 C5.14453043,5.90624684 5.24999812,5.40234563 5.625,5.02734375 L5.625,4.95703125 C5.60156238,4.91015602 5.58984375,4.87500012 5.58984375,4.8515625 C5.12109141,3.28124215 5.08593551,2.20312793 5.484375,1.6171875 C5.76562641,1.31249848 6.10546676,1.13671898 6.50390625,1.08984375 C6.90234574,0.386715234 7.91014816,0.0234376172 9.52734375,0 C9.80859516,0 10.1132796,0.0234372656 10.4414062,0.0703125 C12.0117266,0.257813437 12.8906241,0.80858918 13.078125,1.72265625 C13.2187507,2.42578477 13.0195339,3.45702445 12.4804688,4.81640625 C12.4804688,4.83984387 12.4628908,4.88085908 12.4277344,4.93945312 C12.3925779,4.99804717 12.375,5.03906238 12.375,5.0625 C12.7265643,5.41406426 12.832032,5.90624684 12.6914062,6.5390625 C12.6210934,6.84375152 12.4921884,7.08984281 12.3046875,7.27734375 C12.2578123,8.12109797 11.9531278,8.8828091 11.390625,9.5625 L11.390625,11.4960938 C11.9765654,11.7070323 12.339843,11.8359373 12.4804688,11.8828125 C13.1835973,12.1406263 13.6757798,12.3281244 13.9570312,12.4453125 C15.7851654,13.1718786 16.8749982,13.8515593 17.2265625,14.484375 Z"></path>
                        </svg>
                    </a>
                    <a class="user-notification" href="#">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="17" viewBox="0 0 18 17">
                            <path fill="#aab6c2" fill-rule="evenodd" d="M17.7890625,14.2734375 C17.9062506,14.3203127 17.9765624,14.4257804 18,14.5898437 C17.9531248,14.7304695 17.8476571,14.8124999 17.6835938,14.8359375 L0.31640625,14.8359375 C0.175780547,14.8124999 0.0703128516,14.7304695 0,14.5898437 C0.0234376172,14.449218 0.0937494141,14.3437504 0.2109375,14.2734375 C0.234375117,14.2734375 0.257812383,14.2617189 0.28125,14.2382812 C1.68750703,13.886717 2.390625,13.2890667 2.390625,12.4453125 L2.390625,8.26171875 C2.390625,7.46483977 2.51952996,6.67969137 2.77734375,5.90625 C3.43359703,4.05467824 4.67577211,2.75391 6.50390625,2.00390625 C6.55078148,1.74609246 6.64453055,1.50000117 6.78515625,1.265625 C7.27734621,0.421870781 8.01562008,0 9,0 C9.28125141,0 9.56249859,0.0468745313 9.84375,0.140625 C10.7578171,0.445314023 11.3085928,1.06640156 11.4960938,2.00390625 C12.0820342,2.26172004 12.6445286,2.58984176 13.1835938,2.98828125 C14.8007893,4.32422543 15.609375,6.08202035 15.609375,8.26171875 L15.609375,12.4453125 C15.6328126,13.2656291 16.3593679,13.874998 17.7890625,14.2734375 Z M10.7929688,15.5390625 C10.9570321,15.5625001 11.0624998,15.6562492 11.109375,15.8203125 C11.109375,17.2265695 10.406257,17.9296875 9,17.9296875 C7.59374297,17.9296875 6.890625,17.2265695 6.890625,15.8203125 C6.91406262,15.6796868 7.01953031,15.5859377 7.20703125,15.5390625 L10.7929688,15.5390625 Z"></path>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="header-panel__right">

                <div class="profile-box__dropdown">
                    <div class="profile-box">
                        <div class="profile-avatar"></div>
                        <div class="profile-name">{{name}}Имя фамилия</div>
                        <div class="dropdown-menu">
                            <a href="#">Настройки</a>
                            <a href="#">Выйти</a>
                        </div>
                    </div>
                </div>

                <div class="header-panel__exit-help">
                    <a href="#">Помощь</a>
                    <a href="#">Выход</a>
                </div>
            </div>
        </div>
    </header>
</template>

<style>
header {
    width: 100%;
    height: 55px;
    background-size: cover;
    position: sticky;
    background-color: aliceblue;
}
.header-wrapper__panel {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-around;
}
.header-panel__left {
    display: flex;
    flex-direction: row;
    align-items: center;
    box-sizing: border-box;
    justify-content: left;
}
.header-panel__right {
    display: flex;
    flex-direction: row;
    align-items: center;
    box-sizing: border-box;
    justify-content: right;
}
.header-panel__left .header-logotype {
    height: 30px;
    width: 30px;
    background-image: url('../assets/img.png');
    background-size: cover;
    background-repeat: no-repeat;
    border: 1px solid transparent;
    border-radius: 25px;
}

.header-notification {
    margin-top: 16px;
    min-width: 120px;
}
.header-notification svg {
    width: 20px;
    margin-left: 5px;
    height: 15px;
}
.header-notification path:hover {
    fill: #828385;
}



.profile-box__dropdown {
    display: flex;
    flex-direction: row;
    align-items: center;
    box-sizing: border-box;
    justify-content: right;
}
.profile-box__dropdown .profile-box .dropdown-menu{
    display: none;
}
.profile-box__dropdown .profile-box {
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    box-sizing: border-box;
    border: 1px solid transparent;
    border-radius: 10px;
}
.profile-box__dropdown .profile-box .profile-avatar {
    height: 30px;
    width: 30px;
    background-image: url('../assets/img.png');
    background-size: 100%;
    background-repeat: no-repeat;
    border: 1px solid transparent;
    border-radius: 20px;
}
.profile-box__dropdown .profile-box:hover {
    background-color: rgb(131, 132, 134, 0.8);
    cursor: pointer;
}

.header-panel__exit-help {
    display: flex;
    flex-direction: column;
}
.header-panel__exit-help a{
    font-size: 10px;
    color: #828385;
}

@media screen and (max-width: 769px) {
    .header-wraper__panel {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
}
    .header-panel__left {
    display: flex;
    flex-direction: row;
    align-items: center;
    box-sizing: border-box;
    justify-content: left;
    margin-left:5px ;
}
    .header-panel__right {
    display: flex;
    flex-direction: row;
    align-items: center;
    box-sizing: border-box;
    justify-content: right;
    margin-right: 5px;
}
    .header-panel__exit-help {
        display: none;
    } 
}
</style>