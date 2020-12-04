<template>
    <div class="container">
        <div class="rent">
            <h1 class="rent__text">Rent <span>whatever</span></h1>
            <div class="add">
                <span class="add__text">Add new</span>
                <button class="add__btn">+</button>
            </div>
        </div>
        <rent-item></rent-item>
    </div>
</template>

<script>
import RentItem from './rentitem'
    export default {
        name: 'rent-block',
        components: {
            RentItem
        }
    }
</script>

<style scoped>
.container {
    max-width: 1312px;
    margin: 0 auto 48px;
    box-sizing: border-box;
    padding: 64px;
    border-radius: 48px;
    background-color: #F3F4F7;
}
.rent {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.rent__text {
    font-size: 40px;
    font-family: 'Codec Pro', sans-serif;
}
.rent__text span {
    color:  #4959FF;
}
.add {
    width: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.add__text {
    font-family: 'Codec Pro', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 140%;
    color: #4959FF;
    cursor: pointer;
}
.add__btn {
    width: 48px;
    height: 48px;
    background: #4959FF;
    border-radius: 16px;
    border: none;
    color: #fff;
    cursor: pointer;
    font-size: 25px;
}
.add__btn:hover {
    background-color: #F3F4F7;
    color: #4959FF;
    font-weight: bold;
}
@media (max-width: 860px) {
    .rent__text {
        font-size: 22px;
    }
}
</style>