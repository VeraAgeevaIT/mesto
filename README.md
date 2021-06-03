# Проектная работа 9: Место

### Проектная работа №9.
#### Исполнитель                                  *Агеев Дмитрий* 

<p align="center"><img src="https://scontent.fmsq2-1.fna.fbcdn.net/v/t1.6435-9/127142444_1292068024474820_2603593254457549792_n.jpg?_nc_cat=102&ccb=1-3&_nc_sid=174925&_nc_ohc=Hd9b4qpeByUAX9YLldF&_nc_ht=scontent.fmsq2-1.fna&oh=3c2b650bdc32fe1af6868ea0840e276d&oe=60BF3499" width="200" alt="Агеев Дмитрий"></p>

##### Обзор ПР №9
Сайт представляет собой 9ую проектную работу в рамках курса "Яндекс.Практикума" по веб-разработке, когорта 24. Это учебный проект, в котором сверстана страница профиля сервиса по публикации фотографий из путешествий. На странице присутствует информация о пользователе (фото профиля, имя, небольшая информация) и грид из фотографий. Предусматривается возможность добавить новую фотографию, удалить фотографию, просмотреть фотографию фулвью, поставить лайк, отредактировать аватарку и имя пользователя.

<p align="center"><img src="https://yandex.by/images/search?p=1&text=spinner+js&pos=63&rpt=simage&img_url=https%3A%2F%2Fsun9-3.userapi.com%2Fc854328%2Fv854328094%2F1e9f6b%2FrJrE1EEJisI.jpg&from=tabbar" width="300" alt="spinner"></p>



В рамках текущей учебной работы разработана связь сервиса c cервером по API. Изменения, сделанные в браузере, сохраняются на сервере (лайки, добавленные фотографии, информация о пользователе). При изначальной загрузке страницы рендерится массив фотографий с сервера. Добавлен лоудер на момент сабмита данных на сервер.

##### Использованные технологии:
* JS, popup
* flexbox, grid
* медиазапросы
* верстка по figma
* верстка по адаптивному макету
* организация файлов по БЭМ методологии
* внедрение TEMPLATE-элементов в Html для работы с шаблоном ввода карточек и повышения безопасности сайти при работе с введением запросов клиентов через input
* добавление и удаление карточек, а также лайков пользователем сайта самостоятельно, реализовано через функции JavaScript
* плавное открытие и закрытие попапов с использованием visibility: hidden;   opacity: 0;  transition: visibility 0s, opacity 0.5s linear; visibility: visible; opacity: 1;
* разработана валидацию всех форм API-свойством validity.valid - проверка валидности формы на стороне клиента
* улучшен UX при работе с попапами.
* инициализация npm и настройка Webpack
* настроил сборку Вебпаком)


**Figma**

* [Ссылка на макет в Figma](https://www.figma.com/file/2cn9N9jSkmxD84oJik7xL7/JavaScript.-Sprint-4?node-id=28212%3A269)

**Картинки**

Фотографии брал не из макета FIGMA, а с сайта https://unsplash.com — это коллекция бесплатных фотографий,
которые можно использовать, не беспокоясь об авторских правах.
+ также не забыл [оптимизировать картинки](https://tinypng.com/), чтобы сайт загружался быстрее.

[Посмотрите мой проект MESTO на GitHub Pages.](https://ageevdmitryminsk.github.io/mesto/src/index.html)

https://ageevdmitryminsk.github.io/mesto/src/index.html

* C Днём начала лета 9 июня ♥♥♥!!!

##                  *2021*                     ЯндексПрактикум рулит) 🏎

*Чем большим числом программ вы владеете, тем проще вольётесь в любой проект.*
