# Viewport_API
Вставка страницы через iframe с автоматическим определением размеров

1\. Полкочите **dispathcer.js** в **index.html**
<br/>2\. Добавьте тег iframe c пустым аттрибутом src и id="iframe":
```html
<iframe id="iframe" frameborder="0"></iframe>
```
3\. Инициализируйте viewport в **index.html**:
```javascript
viewport.init('URL страницы, которую подтягиваем через iframe');
```
4\. Подключите **client.js** в подтягиваемую страницу (назовем **iframe.html**)
<br/>5\. Инициализируйте viewoprt в **iframe.html**:
```javascript
iframeParent.init('URL родительского окна');
```
