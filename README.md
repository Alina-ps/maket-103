# maket-103

<!-- 1 lesson online -->
<!-- doctype html вказівник яка версія html використовується -->

      <!-- create list fast for ex ul>li*3>a unordered list with 3 li with links
    Chocolate is loved (cheat sheet)-->
      <!-- remove вразливість сайту rel="noopener noreferrer" -->
            <!-- лого це завжди посилання -->

<!-- 2 lesson online -->

1. in document it is not important to use h1 only once but in reality we use only once
2. always compress files, for example for png can use site https://compresspng.com/
3. multicurser press alt and click on fields
4. work from left to right from up to down

<!-- урок з ментором перший в групах -->

1. якщо не додати доктайп то нічого не буде, браузер все рівно прочитає (мо просто допомогаємо цим йому)

<!-- 3 lesson online (css)-->

1. tag wrap -> alt+W highlight part of code and press alt+W
2. header can be several times on one page, it can be connected to special section
3. interesting article about CSS https://webdesign.tutsplus.com/uk/the-30-css-selectors-you-must-memorize--net-16048t
4. in css we can refer to atribute by [href] and write styles for it. used seldom
5. каскад стилів - при умові однакової специфічності перемагає той що в списку css нижче знаходиться
6. in one class you can put several classes with slash like: stype='link header-link'
7. for ul can use list-style: none or list-style-type: none
8. ctrl+f to change for example one element on another (in file)
9. ctrl+shift+f change in the whole folder
10. sheck styles in browser: site -> right click -> inspect -> computed

<!-- 4 lesson online (css) -->

1. базові основи терміналу часто запитують на співбесідах
2. завдяки розширенню ecss tractor we can copy part of the code right click and put in css classes from html
3. button does not inherit font-family
4. by default in browser font-weight is 400 so we can remove it in paragraf
5. if we want to hide h2 on page but not destroy semantic plus leave it visible for browser we can use css pattern
   .visually-hidden {
   position: absolute;
   width: 1px;
   height: 1px;
   margin: -1px;
   border: 0;
   padding: 0;

white-space: nowrap;
clip-path: inset(100%);
clip: rect(0 0 0 0);
overflow: hidden;
}

6. практики accessability? semantic, atribute tel, mailto;

<!-- 5 lesson online (module 3 flexbox) -->

1. поставити в домашці box-sizing: border-box (ця властивість використовується завжди)
   як правило прописують на селектор \* {box-sizing: border-box}
   прописано в нормалайз тому не треба ставити
2. завдяки палінгу можна збільшувати ссилки
3. падінг не працює на інлайнових елементах (не обов'язково)
4. задати падінги для карточек з фото людей
5. маржин тільки між сусідами
6. не ставити flex для рядкових елементів
7. nth-child (5), nth-child() nth-last-child (an+b) (reverse)
8. https://codepen.io/tea246/pen/WLEJMK
9. скидання стилів
10. власні стилі в лінках повинні бути останніми
11. margin: 0 auto; ставить по центру батька
12. max-width не більше вказаною, ширина будь яка але не більше ніж вказаної
13. https://github.com/riko1212/fs-103

<!-- 6 lesson online (module 3 flexbox) -->

1. justify-content: center (can use to put elements in center)
2. use game space frog to play with flex (is in lectures)
3. головна вісь за замовчуванням горизонтальна і зліва направо
4. aling-content (seldomly used) but can ask on interview
5. flex-grow by default is 0, flex-shrink by default 1
6. щоб текст не стискав елемент у флексу треба задати флекс шрінк 0
7. order дозволяє змінювати порядок елементів, задає вагу, за замовчуванням 0 тому якщо 1 це другий, 2 третій, -1 перед 0, при умові однакових ордерів порядок по html
8. елементи флексу автоматично стають блоковими

<!-- 7 lesson online (module 4 part 1) -->

1. margin: 0 auto is to put in the center content
2. pseudoelement selection (when we highlight text, the color of highlight)
3. background-image: url()
4. ../img/.... треба писати дві крапки бо нам треба вийти з папки css
5. background-repeat: no-repeat (when you don't want to repeat img, by default it is repeat)
6. background-position: center center (гоизонталь вертикаль)
7. can write once center, друга властивість по дефолту буде центре якщо не прописати
8. якщо прописати бекграунд сайз у відсотках воно буде ставить зображення пропорційно ширині фрейму
9. при bacground-size: contain зображення буде або звужуватись або розтягуватись щоб заповнити максимум фрейму, в межах фрейму і залишаючи пропорції
10. градієнт linear з background-image, background-image: linear-gradient (це функція) {direction, color, color}
11. background-image: linear-gradient {color 0 40%, color}
12. box-shadow: inset(внутрішня) 0(Зміщення по осі x) 0(Зміщення по осі y) 0(blur) 0() 0(color)
13. box-shadow generator, can search on internet
14. ::before by default is inline element
15. sprite with css does not work, only with html
16. highlight part of code then alt+W and write tag you want
