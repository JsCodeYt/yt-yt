<template>
    <div class="view">
        <h1>Как происходит обучение на YtYt?</h1>
        <span>Обучение должно быть комфортным. Поэтому мы разработали собственную платформу для обучения
            программированию. На ней вы можете не только изучать теорию, но и запускать готовые примеры и даже писать
            свой собственный код.
        </span>
        <div class="view__imgs">
            <img src="../assets/Group 1178.png" alt="">
            <img class="play" src="../assets/Group 1193.png" alt="">
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.view {
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.view h1 {
    font-size: 40px;
    color: #22253B;
}

.view span {
    width: 500px;
    margin: 10px 0px;
    font-size: 12px;
    text-align: center;
}

.view__imgs {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    -webkit-box-shadow: -1px 4px 29px 0px rgba(34, 60, 80, 0.2);
    -moz-box-shadow: -1px 4px 29px 0px rgba(34, 60, 80, 0.2);
    box-shadow: -1px 4px 29px 0px rgba(34, 60, 80, 0.2);
    margin-top: 30px;
}

.play {
    position: absolute;
    top: 34%;
}
</style>