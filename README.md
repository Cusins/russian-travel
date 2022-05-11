Ссылка на проект: https://cusins.github.io/russian-travel/index.html

### Проектная работа №3: Russian Travel
---
**Описание**
1. В проекте есть index.html , index.css , README.md, директория blocks со стилями и файлы с картинками в
директории images .
2. В index.css импортирован normalize.css .
3. Верстка внешне соответствует макету в брифе.
4. Нет опечаток в коде HTML и CSS, страница валидна
5. Стили подключены в отдельном файле.
6. Присутствуют все секции из макета.
7. Вёрстка не ломается между брейкпоинтами.
8. Ширина элементов и отступы отличаются от макета не больше, чем на 30px на контрольных точках.
9. Для различных блоков, заголовков, секций и т.д применяются соответствующие теги
10. Все ссылки и интерактивные элементы имеют состояние наведения :hover .
11. Контентные изображения имеют alt с корректным описанием, которое соответствует языку страницы.


**Новые технологии, не используемые в предыдущих проетах:**


1. Адаптивная верстка с медиазапросами
```css
@media (max-width: 425px) {
  .header {
    padding: 16px 16px 0;
  }
}

```
2. Grid - layout
```css
.photo__list {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, 1fr);
  gap: 16px;
  margin: 0;
}
```
3. Figma  ([Ссылка на макет](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0))

4. Подключение шрифтов
```css
@font-face {
  font-family: 'Intel';
  src: url(../../fonts/Inter-Black.woff);
  src: url(../../fonts/Inter-Black.woff2);
  font-weight: 900;
}

@font-face {
  font-family: 'Intel';
  src: url(../../fonts/Inter-Bold.woff);
  src: url(../../fonts/Inter-Bold.woff2);
  font-weight: 700;
}

@font-face {
  font-family: 'Intel';
  src: url(../../fonts/Inter-Regular.woff);
  src: url(../../fonts/Inter-Regular.woff2);
  font-weight: 400;
}
```
5. Оптимизация изображений
6. Создание новых веток Git
