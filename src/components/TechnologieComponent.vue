<template>
    <div class="container">
        <h1 class="title">THE SKYLS</h1>
        <div class="wrapper">
            <div>
                <img src="../../public/html.png" alt="Html">
                <p>HTML</p>
            </div>
            <div><img src="../../public/css.png" alt="Css">
                <p>CSS</p></div>
            <div><img src="../../public/js.png" alt="Javascript">
                <p>JavaScript</p></div>
            <div><img src="../../public/vue.png" alt="Vue Js3">
                <p>VueJs3</p></div>
        </div>
        <div class="wrapper">
            <div><img src="../../public/node.png" alt="Node js">
                <p>Node Js</p></div>
            <div><img src="../../public/php.png" alt="php">
                <p>Php</p></div>
            <div><img src="../../public/laravel.png" alt="Laravel">
                <p>Laravel</p></div>

        </div>
        <div class="wrapper">
            <div><img src="../../public/mysql.png" alt="Mysql">
                <p>MySql</p></div>
            <div><img src="../../public/git.png" alt="Git">
                <p>Git</p></div>
        </div>
    </div>
</template>
<style scoped>
.container {
    margin: 5rem auto;
}
.title {
    text-align: center;
    font-size: 3rem;
}
.wrapper {
    display: flex;
    justify-content: center;
}

.wrapper>div {text-align: center;
    background-color: #dbd7d7;
    margin: 2rem;
    width: 15rem;
    height: 15rem;
    border-radius: 1rem;

}
img {
    width: 6rem;
    position: relative;
    margin:2rem auto;
}
p {
    font-size: 1.5rem;
    font-weight: bold;
}
@media screen and (max-width:900px) {
    .wrapper{
        display: block;
        text-align: center;
       
    }
    .wrapper>div {text-align: center;
    background-color: #dbd7d7;
    margin: 2rem;
    width: 25rem;
    height: 15rem;
    border-radius: 1rem;
    margin: 1rem auto;

}
}
</style>
