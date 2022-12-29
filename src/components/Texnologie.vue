<template>
    <h1 class="tex__title">
        Какие технологии вы изучите:
    </h1>
    <div class="container">
        <div class="tex" data-aos="fade-up">
            <div class="tex__imgs">
                <img src="../assets/Group 1175.png" alt="">
            </div>
            <div class="tex__tex">
                <div class="tex__item blue">
                    Язык программирования Python
                </div>
                <div class="tex__item orange">
                    Сети
                </div>
                <div class="tex__item red">
                    Базы данных
                </div>
                <div class="tex__item mediumblue">
                    Фреймворки Flask и Django
                </div>
                <div class="tex__item blue">
                    Docker
                </div>
                <div class="tex__item git">
                    Git
                </div>
                <div class="item__info">
                    Это необходимый минимум для современного backend-разработчика
                </div>
            </div>
        </div>
    </div>
</template>
<script>

export default {
}
</script>
<style scoped>
.container {
    margin-top: 20px;
    height: 500px;
    background-color: #EAF2F5;
    border-radius: 50px;
}

.tex {
    display: flex;
    gap: 2rem;
    justify-content: center;
}

.tex__title {
    text-align: center;
}

.tex__imgs>img {
    margin: 60px 17px;
}

.tex__tex {
    margin-top: 60px;
    width: 500px;
}

.tex__item {
    margin: 5px;
    padding: 10px 30px;
    border-radius: 50px;
    display: inline-block;
    color: #FFFFFF;
}

.item__info {
    margin-top: 70px;
}

.tex__item.blue {
    background-color: #5096FF;
}

.tex__item.mediumblue {
    background-color: #50C0FF;
}

.tex__item.orange {
    background-color: #FFB359;
}

.tex__item.red {
    background-color: #FF6F50;
}

.tex__item.green {
    background-color: #4BD071;
}

.tex__item.git {
    background-color: #AF93FF;
}
</style>