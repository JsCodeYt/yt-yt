<template>
    <div class="cardInfo" data-aos="fade-up">
        <div class="card">
            <span>01</span>
            <h3>Весь материал разбит на небольшие уроки</h3>
            <p>Теория и практика подаются маленькими порциями. Так вам будет легче усваивать новые знания.</p>
        </div>
        <div class="card">
            <span>01</span>
            <h3>Весь материал разбит на небольшие уроки</h3>
            <p>Теория и практика подаются маленькими порциями. Так вам будет легче усваивать новые знания.</p>
        </div>
        <div class="card">
            <span>01</span>
            <h3>Весь материал разбит на небольшие уроки</h3>
            <p>Теория и практика подаются маленькими порциями. Так вам будет легче усваивать новые знания.</p>
        </div>
    </div>
    <div class="cardBtns">
        <button>
            Начать обучение
        </button>
        <span>Попробуйте, первые уроки бесплатны, но нужно пройти тестирование</span>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.cardInfo {
    margin-top: 30px;
    background-color: #efefef;
    height: 200px;
    margin-top: 30px;
    border-radius: 50px;
    padding: 50px;
    display: flex;
    gap: 1rem;
}

.card {
    width: 300px;
    height: 300px;
    padding: 5px;
}

.card span {
    font-size: 60px;
    font-weight: 600;
    color: #38BFF2;
}

.card h3 {
    font-size: 20px;
    margin: 10px 0px;
}

.card p {
    font-size: 16px;
}

.cardBtns {
    margin-top: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}

.cardBtns button {
    padding: 20px 40px;
    background-color: #F15525;
    color: white;
    border-radius: 50px;
    border: none;
    outline: none;
    display: flex;
    align-items: center;
}

.cardBtns span {
    width: 300px;
}
.btn__icon {
    display: inline-block;
}
</style>