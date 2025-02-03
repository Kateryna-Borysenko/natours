<!-- анимация  https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function

.heading-primary--main {
  display: block;
  font-size: 6rem;
  font-weight: 40rem;
  letter-spacing: 3.5rem;

  animation-name: moveInLeft;
  animation-duration: 1s;

  animation-timing-function: ease-out;
  /*
    animation-delay: 3s; задержка анимации
    animation-iteration-count: 3; количество повторений анимации
  */
}


html {
  1rem = 10px
  10/16 = 62.5% для универсальности например если у пользовтеля установлен более крупный или мелкий шрифт а не тот что по умолчанию 16px, поэтому значение в процентах позволяет избежать этих проблем  */
  font-style: 10px; мы могли бы написать так

  font-size: 62.5%; но это лучшая практика
}
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274436#content


как сделать градиент заголовок
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274490#content

иконки
https://linea.io/

обработка картинок:
background-blend-mode: screen; варианты в devtools
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274502#content

бесплатные видео https://coverr.co/

создание текста из нескольких колонок popup
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274530#content
    -moz-column-count: 2;
    -moz-column-gap: 4rem;
    -moz-column-rule: 1px solid $color-grey-light-2;

    column-count: 2;
    column-gap: 4rem;

перенос слов
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274530#content
    -moz-hyphens: auto;
    -ms-hyphens: auto;
    -webkit-hyphens: auto;
    hyphens: auto;

почему лучше использовать em в @media запросах
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274548#content

html {
  font-size: 62.5%;
  //1 rem = 10px; 10px/16px = 62.5%
  scroll-behavior: smooth;

  @include respond(tab-land) {
    // width < 1200?
    font-size: 56.25%; //1 rem = 9px, 9/16 = 50%
  }

  @include respond(tab-port) {
    // width < 900?
    font-size: 50%; //1 rem = 8px, 8/16 = 50%
  }

  @include respond(big-desktop) {
    font-size: 75%; //1rem = 12, 12/16
  }
}

последовательность при написании @media
base typography layout grid page components

тестирование медиа запросов на реальном устройстве
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274554#content
sizzy - https://sizzy.co/


как проверить какое изображение загрузилось 1х 2х
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274562#content
размер для разных экранов
https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8274562#content

-->
