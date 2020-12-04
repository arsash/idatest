<template>
    <div class="rent__container">
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 3.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">1 278 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 4.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 5.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 5.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 6.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">1 278 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 3.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 4.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 7.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 6.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">1 278 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 5.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 5.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
        <div class="rent__item">
            <div class="rent__item__img">
                <img src="../assets/rentItemImg/Rectangle 5.png" alt="Item image">
            </div>
            <div class="rent__item__info">
                <p class="rent__item__name">XR-74 «Cooper»</p>
                <p class="rent__item__text">Brief description of the project,<br>in a few lines.</p>
                <p class="rent__item__price">164 $/h</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'rent-item'
    }
</script>

<style scoped>
.rent__container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.rent__item {
    width: 310px;
    height: 120px;
    background: #FCFCFC;
    border-radius: 32px;
    padding: 24px;
    margin-top: 40px;
    display: flex;
    cursor: pointer;
}
.rent__item:hover {
    transform: scale(1.1);
    transition: 0.7s;
}
.rent__item__img {
    margin-right: 24px;
}
.rent__item__name {
    font-family: 'Codec Pro', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 14px;
    color: #012345;
}
.rent__item__text {
    font-family: 'Codec Pro', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 12px;
    line-height: 148%;
    color: #677B8F;
}
.rent__item__price {
    font-family: 'Codec Pro', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 148%;
    color: #F84AB3;
}

@media (max-width: 860px) {
  .rent__container {
    justify-content: center;
  }
}
</style>