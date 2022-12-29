<template>
    <div class="container">
        <div class="cards__title">
            <h1>Обучение в YtYt – это удобно и результативно</h1>
        </div>
        <div class="cards">
            <div class="card" data-aos="fade-left">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-rigth">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-left">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-right">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-left">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-rigth">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
            </div>
            <div class="card" data-aos="fade-left">
                <img src="../assets/svg-gobbler 1.png" alt="">
                <p>Огромное количество практики</p>
                <span>Более 500 самостоятельных заданий и 20 полноценных больших проектов</span>
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
    padding: 0px 100px;
}

.cards__title {
    justify-content: center;
    text-align: center;
    display: flex;
}

.cards__title h1 {
    width: 500px;
    color: #22253B;
    font-size: 40px;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 40px;
    justify-content: center;
}

.card {
    width: 300px;
    background-color: #EAF2F5;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 1rem;
    height: 250px;
    border-radius: 20px;
}

.card img {
    height: 40%;
    width: 30%;
    object-fit: contain;
}

.card p {
    font-weight: 500;
    width: 200px;
    font-size: 20px;
}

.card span {
    padding: 0px 20px;
}
</style>