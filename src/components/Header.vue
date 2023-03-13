<template>
    <header>
        <div class="container">
            <div class="box-logo">
                <img class="logo" src="" alt="LOGO">
            </div>
            <div>
            <ul class="menu-list">
                <li>
                    <a href="">Home <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
                <li>
                    <a href="">Pages <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
                <li>
                    <a href="">Courses <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
                <li>
                    <a href="">Features <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
                <li>
                    <a href="">Blog <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
                <li>
                    <a href="">Shop <i class="fa-solid arrow fa-angle-down"></i></a>
                </li>
            </ul>
            </div>
            <div class="menu-search">
                <div class="menu-search">
                    <div class="box-flag">
                        <img src="/Bandiera-Inglese.png" alt="">
                    </div>
                    <p>ENGLISH <i class="fa-solid arrow fa-angle-down"></i></p>
                    <i class="fa-regular fa-circle-user"></i>
                </div>
                <div>
                    <input class="input-search" type="text" placeholder="Search">
                </div>
            </div>
        </div>
    </header>
</template>



<script>


</script>



<style lang="scss" scoped>
.container {
    display: flex;
    justify-content: space-between;
    line-height: center;
    color: #343142;
    // background-color: aquamarine;

    .box-logo {
        margin-left: 120px;
        .logo {
            margin-top: 30px;
        }
    }
    .input-search {
        border: none;
        padding: 32px;
    }

}
.menu-list {
    display: flex;
    gap: 49px;
    margin-top: 30px;

    .arrow {
        font-size: 10px;
    }
}

.box-flag {
    width: 38px;
    height: 33px;
}

.menu-search {
    display: flex;
    align-items: center;
    gap: 14px;
}




</style>
