<template>
    <div class="subheader">
        <ul class="subheader-wrapper">
            <li class="subheader-menu">
                <a class="subheader-menu__link" id="education" href="#">оброзование</a>
                <ul class="link-item" id="item-education">
                    <li>item__education</li>
                    <li>item__education</li>
                    <li>item__education</li>
                    <li>item__education</li>
                </ul>
            </li>
            <li class="subheader-menu">
                <a class="subheader-menu__link" href="#">оброзование</a>
                <ul class="link-item">
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>   
            </li>
            <li class="subheader-menu">
                <a class="subheader-menu__link" href="#">оброзование</a>
                <ul class="link-item">
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul> 
            </li>
            <li class="subheader-menu">
                <a class="subheader-menu__link" href="#">оброзование</a>
                <ul class="link-item">
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul> 
            </li>
        </ul>
    </div>
</template>

<style>
.subheader {
    width: 100%;
    height: 50px;
    background-size: cover;
    background-color: #0273b2;
    position: sticky;
    display: flex;
    justify-content: center;
    align-content: space-around;
}
.subheader-wrapper {
    margin: 0px;
}
.subheader-menu {
    list-style-type: none;
    display: inline-block;
    height: 4.5vh;
    line-height: 4.5vh;
}
.subheader-menu__link {
    height: 100%;
    padding: 0 2.0vh;
    color: #fff;
    background-color: #0273b2;
    text-decoration: none;
    font-size: 1.5vh;
    text-transform: uppercase;
    position: relative;
    letter-spacing: 0.1vh;
}
.link-item {
    display: none;
}

</style>