Набор полезных ссылок для начинающих фронтендеров
======

Хочу кинуть вам несколько супер полезных и интересных ссылок, чтобы вам было что читать и дать несколько полезных советов

## REST API + CRUD
Эти вещи используются повсеместно в веб разработке и в нашем проекте они тоже будут нужны.
Про рест лучше читать не на русской википедии - там откровенно говоря, не статья, а __фу__. Есть много статей на хабре и в интернете вообще. Есть так же и видео на [ютубе](https://www.youtube.com/watch?v=6OdJ4GGyRxc). Чтобы вы поняли, рест - это просто некоторый подход к проектированию АПИ. Совместно с CRUD, например, эта методология позволяет ответить на вопрос, какой запрос нужно выполнить, чтобы изменить логин у пользователя с идентификатором `id78238479`? Правильный ответ
```
PATCH /api/users/id78238479
{ "login": "JonSnow" }
```
и фишка в том, что посмотрев на этот запрос, почти каждый разработчик ответит, что этот запрос сделает.

## BEM
Это методология разработки HTML-компонентов. Нам, в частности, понадобится т.н. `bem-naming` - т.е. именование css-селекторов. Есть официальный сайт яндекса и тоже много всяких статей на хабре. Сразу настраиваю вас отказаться от использования каких-либо библиотек стилей, хотелось бы, чтобы вы сделали дизайн самостоятельно))

## CSS
Подучите css. В настоящее время с помощью css можно делать просто умопомрачительные вещи. Посмотрите на такие свойства и возможности, как
- css transitions
- keyframes
- css custom propetries
- css трансформации
- css фильтры

Поищите в инете всякие сайты, где выкладывают подборки ресурсов для фронтендеров. Например [группа](https://vk.com/webtackles) содержит много ссылок на различные css-эффекты.

## SASS
Тру фронтендеры не пишут чистый css, а используют для этого препроцессоры, less, sass, или даже постпроцессоры (postcss). Нам будет достаточно научиться SASS'у (удобнее имхо использовать его разновидность - SCSS).

## git
Нужен и нам и вообще

[githowto.com](https://githowto.com/ru) - потратьте час и пройдите его. Очень полезно вам будет.

## js
Вот мы и добрались до самого интересного. Ваши постоянные друзья:
#### [learn.javascript.ru](https://learn.javascript.ru/)
хрестоматия js - советую до первого РК прочитать всё, начиная с введения, и заканчивая главой "Методы объектов и контекст вызова". Это всё вам понадобится уже на первом РК

#### [developer.mozilla.org](https://developer.mozilla.org/ru/docs/Web/JavaScript)
тоже очень полезный сайт, в котором объяснено не только, как работают те или иные методы в js, но и рассказано про почти все браузерные api. Именно на этом сайте можно посмотреть что вообще умеют браузеры и как использовать те или иные возможности

#### [Скринкаст по ноде](https://learn.javascript.ru/screencast/nodejs)
скринкаст по Node.JS - первые 9 видео обязательны к просмотру. Остальные - по желанию, но вам они будут и полезны и интересны, я уверен. Тем более это не очень много времени у вас отнимет

#### [Frontender Magazine](http://frontender.info/)
очень крутой сайт. На нём есть масса статей, так или иначе связанных с вебом. Много статей про js, как высокого уровня сложности, так и достаточно простых. Вообще отличный ресурс, например [эта статья](http://frontender.info/basic-css-selectors-explained-with-cats/)

#### [javascriptweblog.wordpress.com](https://javascriptweblog.wordpress.com/2011/02/07/truth-equality-and-javascript/#more-2108)
суперская статья про типы данных в js - обязательно к прочтению. Ну и вообще интересный сайт.

#### [caniuse.com](http://caniuse.com/)
вот это дело вы будете использовать постоянно) советую запомнить

#### И ещё немного ссылок:
* http://prgssr.ru/
* https://vk.com/jsraccoon
* https://htmlacademy.ru/blog/tags/%D0%BF%D0%BE%D0%BB%D0%B5%D0%B7%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B0
* https://www.youtube.com/channel/UCMtlICYxr6Dz_PG9_SVqRYQ
* http://forwebdev.ru/

