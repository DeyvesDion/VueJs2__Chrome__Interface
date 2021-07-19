<template>
    <div class="accueil">
        <div class="accueil__banner">
            <div class="icon__wrapper">
                <span class="icon__left circle"
                    ><i class="fas fa-arrow-left"></i
                ></span>
                <span class="icon__right circle"
                    ><i class="fas fa-arrow-right"></i
                ></span>
                <span class="icon__refresh circle"
                    ><i class="fas fa-redo-alt"></i
                ></span>
            </div>
            <div class="search__bar">
                <div class="search__form">
                    <div class="item_left">
                        <span class="icon__left circle"
                            ><i class="fas fa-lock"></i
                        ></span>
                        <span class="search__title"
                            ><h3>localhost : 8080</h3></span
                        >
                    </div>
                    <div class="item_right circle">
                        <span class="icon__right"
                            ><i class="far fa-star"></i
                        ></span>
                    </div>
                </div>
            </div>
            <div class="user">
                <div class="user__img circle"></div>
                <span class="user__icon circle"
                    ><i class="fas fa-ellipsis-v"></i
                ></span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Accueil",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.accueil__banner {
    height: 70px;
    /* background-color: red; */
}
.accueil__banner,
.icon__wrapper,
.user,
.search__form,
.item_left {
    display: flex;
}
.icon__wrapper {
    width: 8.5%;
    align-items: center;
    justify-content: center;
    display: flex;
}
.search__bar {
    width: 65.6%;
    align-items: center;
    justify-content: center;
    display: flex;
}
.search__form {
    width: 100%;
    border-radius: 25px;
    background-color: rgba(128, 128, 128, 0.11);
    align-items: center;
    justify-content: space-between;
    /* display: flex; */
}
.item_left {
    display: flex;
    align-items: center;
    justify-content: center;
}
.user {
    width: 25.9%;
    align-items: center;
    justify-content: space-between;
    display: flex;
}
.circle {
    height: 28px;
    width: 28px;
    cursor: pointer;
    background-color: transparent;
    border-radius: 50%;
    align-items: center;
    justify-content: center;
    display: flex;
    /* display: inline-block; */
}
.circle:hover {
    background-color: rgba(128, 128, 128, 0.11);
}
.fas,
.far {
    font-size: 17px;
    font-weight: 900;
}
.search__bar {
    justify-content: space-between;
}
.item_left {
}
.user {
}
</style>
