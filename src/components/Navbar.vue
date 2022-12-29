<template>
    <div class="navbar">
        <div class="navbar__left">
            <ul class="left__items">
                <li><img src="../assets/Group 1.png" alt=""></li>
                <li class="left__item">Чему вы научитесь</li>
                <li class="left__item">Процесс обучения</li>
                <li class="left__item">Стоимость</li>
                <li class="left__item">Контакты</li>
            </ul>
        </div>
        <div class="navbar__rigth">
            <button class="right__registerBtn">Регистрация</button>
            <button class="right__loginBtn">
                <i class="fa-solid fa-arrow-right"></i>
                Войти
            </button>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.navbar {
    padding: 10px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.left__items {
    display: flex;
    align-items: center;
    list-style: none;
    gap: 1rem;
}

.left__item {
    font-size: 14px;
    cursor: pointer;
}

.navbar__rigth {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.right__registerBtn {
    border: none;
    background-color: #fff;
    font-size: 17px;
    cursor: pointer;
    outline: none;

}

.right__loginBtn {
    background-color: #38BFF2;
    padding: 10px 30px;
    border-radius: 50px;
    outline: none;
    border: none;
    cursor: pointer;
    font-size: 16px;
    color: white;
}
</style>