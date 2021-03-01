<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum vitae</title>
    <link rel="stylesheet" href="stylesheets/style.css">
</head>

<body>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <img class="avatar" src="images/avatar.jpg" alt="avatar">
                <h1 class="header__title">Александр Белоусов</h1>
                <ul class="contacts">
                    <li class="contacts__item"><a href="https://vk.com/tores_kun">vk</a></li>
                    <li class="contacts__item"><a href="https://t.me/">Telegram</a></li>
                </ul>
            </div>
        </div>
    </header>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">About me</h2>
                <p class="about">...</p>
            </div>
        </div>
    </section>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">Skills</h2>
                <ul class="skills">
                    <li class="skill">Системы доступа и видеонаблюдения</li>
                    <li class="skill">Системы ОС и ПС</li>
                    <li class="skill">JavaScript</li>
                    <li class="skill">Git</li>
                    <li class="skill">С++ / C#</li>
                </ul>
            </div>
        </div>
    </section>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">Code example</h2>
                <pre class="code">
function FizzBuzz(n) {
    let arr = [...Array(n+1).keys()];
    let [a, ...b] = arr;
    b.forEach(i => {
        if (i % 15 === 0) {
            console.log("FizzBuzz");
        } else if (i % 3 === 0) {
            console.log("Fizz");
        } else if (i % 5 === 0) {
            console.log("Buzz");
        } else {
            console.log(i);
        }
    });
}
                        </pre>
            </div>
        </div>
    </section>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">Projects</h2>
                <h4 class="project">здесь могла быть ваша реклама :)</h4>
            </div>
        </div>
    </section>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">Education</h2>
                <a href="https://bntu.by/" class="education">BNTY.</a>
            </div>
        </div>
    </section>
    <section class="section">
        <div class="container">
            <div class="section__inner">
                <h2 class="title">English level</h2>
                <h4 class="english">A2(Pre-intermediate)</h4>
            </div>
        </div>
    </section>
    <footer class="footer">
        <div class="container">
            <div class="footer__inner">
                <a class="footer__link" href="https://github.com/tores-kun"></a>
                <a class="footer__link" href="https://app.rs.school/"></a>
            </div>
        </div>
    </footer>
</body>

</html>
