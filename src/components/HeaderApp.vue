<template>
    <header>
        <div class="container-fluid">
            <div class="box-logo">
                <img class="logo" src="/dark-logo.png" alt="LOGO">
            </div>
            <div>
                <ul class="menu-list">
                    <li v-for="el in this.listMenu">
                        <a href=""> {{ el }} <i class="fa-solid arrow fa-angle-down"></i></a>
                    </li>
                </ul>
            </div>
            <div class="menu-search">
                <div class="menu-search">
                    <div class="box-flag">
                        <img src="/en.png" alt="">
                    </div>
                    <span>ENGLISH <i class="fa-solid arrow fa-angle-down"></i></span>
                    <i class="fa-regular fa-circle-user"></i>
                </div>
                <div class="input-search-icon">
                    <input class="input-search" type="text" placeholder="Search...">
                    <div class="icon-search">
                        <i class="fa-solid search-icon fa-magnifying-glass"></i>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>



<script>
export default {
    nome: 'HeaderApp',
    

    data() {
        return {
            listMenu: ['Home', 'Pages', 'Courses', 'Features', 'Blog', 'Shop']
        }
    }

}
</script>



<style lang="scss" scoped>
.container-fluid {
    display: flex;
    justify-content: space-between;
    line-height: center;
    color: var(--font);

    .box-logo {
        width: 160px;
        margin-left: 120px;

        .logo {
            margin-top: 30px;
        }
    }

    .input-search {
        border: none;
        border-left: 1px solid #eceeef;
        font-size: 16px;
        padding-left: 15px;
    }

    li:hover {
        color: #20AD96;
        border-bottom: 1px solid #20AD96;
    }

}

.menu-list {
    display: flex;
    gap: 49px;
    margin-top: 30px;
    color: var(--font);

    .arrow {
        font-size: 10px;
    }
}


.menu-search {
    display: flex;
    align-items: center;
    gap: 14px;
}

.input-search-icon {
    display: flex;
    line-height: 80px;
}

.search-icon {
    font-weight: bold;
    margin-right: 20px;
}
</style>
