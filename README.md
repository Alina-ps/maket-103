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
