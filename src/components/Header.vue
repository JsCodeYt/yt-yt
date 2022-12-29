<template>
    <header>
        <div class="header__info">
            <h2>
                Школа <span class="info__item">
                    {
                </span>программирования<span class="info__item">
                    }
                    <br />
                </span>для тех, кому нужны реальные навыки,
                а не просто сертификат
            </h2>
            <p>
                Пройдите тестирование, чтобы получить доступ к бесплатным вводным урокам
            </p>
            <button>
                Пройти тестирование
                <span class="material-symbols-outlined">
                    arrow_outward
                </span>
            </button>
        </div>
        <div class="header__img">
            <img src="../assets/Layer 2.png" alt="">
        </div>
    </header>
</template>
<script>
export default {

}
</script>
<style scoped>
header {
    display: flex;
    align-items: center;
    margin-top: 50px;
    justify-content: space-between;
    padding: 0px 35px;
}

.header__info {
    width: 700px;
    line-height: 50px;
    font-size: 25px;
    color: #22253B;
    font-weight: 500;
}

.info__item {
    color: #F15525;
}
p {
    font-size: 14px;
    width: 300px;
    line-height: 20px;
}
button {
    margin-top: 30px;
    background-color: #F15525;
    padding: 20px;
    border-radius: 50px;
    color: white;
    font-size: 15px;
    outline: none;
    border: none;
    display: flex;
    align-items: center;
    gap: 10px;
}
</style>