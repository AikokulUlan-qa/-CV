# -CV
Сайт-визитка на  CSS + JS

CSS

body {
  font-family: "Helvetica";
  background-color: #f6f8fa;
  color: #24292f;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.header {
  margin: 40px 0;
}

.header__avatar {
  border-radius: 50%;
}

.header__title {
  margin: 30px 0 10px 0;
  font-size: 32px;
  line-height: 1.2;
  font-family: "Helvetica Neue";
}

.header__subtitle {
  color: #24292f;
  font-size: 16px;
  line-height: 1.4;
  margin: 0;
}

.links {
  width: 320px;
  margin-bottom: 40px;
}

.links__header {
  font-family: "Helvetica Neue";
  font-size: 24px;
  line-height: 1.4;
  margin: 0 0 15px 0;
}

.links__container {
  background-color: #fff;
  list-style-type: none;
  border: 1px solid hsla(210, 18%, 87%, 1);
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 20px 20px 10px;
  gap: 10px;
  flex: none;
  order: 1;
  flex-grow: 0;
  box-sizing: border-box;
  margin: 0;
}

.links__link,
.links__title {
  font-size: 14px;
  font-size: 1.4;
  color: #57606a;
}

.links__link {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px 0px 10px;
  gap: 30px;
  border-bottom: 1px solid hsla(210, 18%, 87%, 1);
  width: 280px;
}

.links__link:last-child {
  border-bottom: none;
}

.linsk__link,
.links__link:visited {
  text-decoration: none;
  color: #0969da;
}

.links__title {
  margin: 0;
  min-width: 100px;
}

footer {
  margin: 0 0 40px 0;
}
.button-link {
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 10px;
  width: 320px;
  background: #fff;
  border: 1px solid rgba(27, 31, 36, 0.15);
  border-radius: 5px;

  font-size: 14px;
  line-height: 1.4;

  color: #0969da;
  text-decoration: none;
}

.button-link:hover {
  background-color: #0969da;
  color: #fff;
  box-shadow: 0 1px 0 rgba(27, 31, 36, 0.1);
}


JS


/* Это объявление переменной, мы наши кнопку по тегу */
const button = document.querySelector('button');

/* Тут на кнопку навешиваем обрабочик, который ждёт клика и тогда запустит логику */
button.addEventListener('click', function() {
	alert('Победи себя и ты выиграешь тысячи битв!')
})


