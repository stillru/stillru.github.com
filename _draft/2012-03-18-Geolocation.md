---
layout: post
title: Умный город - Геолокация
categories:
- SmartCity
---
= Что такое Геолокация?

Современные устройства умеют определять своё положение через различные датчики - от сигналов GSM-сети, сигналов WiFi-сетей, встроенных GPS-чипов, цифровых барометров и прочих. В результате получается информация о том где находится данное устройство и каково его состояние.

Точное определение звучит так : Геолокация - обнаружение реального географического положения (страна, город) компьютера, соединённого с сетью Интернет, мобильного устройства, получаемое на основе IP-адреса, данных, встроенных в программное или аппаратное обеспечение, или другой информации.

Сервисы геолокации получают данный набор координат, обрабатывают его в вид, понятный человеку ( точку на карте ), и позволяют с этой точкой взаимодействовать.

Так же есть термин геолокация - неразрушающее обнаружение и исследование подповерхностных объектов грунтовых сред методом радиолокационного зондирования. Этот термин используется в геологии. Такая чехарда с терминами случилась из-за английского слова geolocation. В русском языке для обозначения данного термина больше подходит слово - геопозиционирование.

= Какие сервисы бывают?

Возможности применения геопозиционирования довольно обширны - от промышленного контроля за автомобилями организации, до персонального поиска потерянного устройства.

Некоторые сервисы позволяют найти ближайший банкомат от места нахождения устройства. Некоторые позволяют получать скидки при регистрации в определённом месте. Некоторые -  блокировать устройство при его краже. Некоторые - включать определённые программы в определённом месте.

= Пользовательские сервисы

Сервисы которые позволяют при их использовании получать скидки в заведениях-участниках сети.

== Foursquare

Foursquare - это первый из сервисов на основе геопозиционирования, который набрал наибольшую популярность в европе и америке.

![4sq](/images/story/4sq.png)

Был запущен в 2009 году и на данный момент насчитывает свыше 15 миллионов человек по всему миру ( по данным на январь 2012 года).

Основная идея сервиса - рассказать своим друзьям о том где ты сейчас находишся. Со временем сервис оброс всевозможными коммерческими предложениями. Например если при первой регистрации в [Кофеин][https://ru.foursquare.com/v/%D0%BA%D0%BE%D1%84%D0%B5%D0%B8%D0%BD/4e16e7dd1fc7d99db5c7a37d] можно получить бесплатный кофе в подарок. Или стать "мэром" [Спа-салона "Коперник"] [https://ru.foursquare.com/v/%D1%81%D0%BF%D0%B0%D1%81%D0%B0%D0%BB%D0%BE%D0%BD-%D0%BA%D0%BE%D0%BF%D0%B5%D1%80%D0%BD%D0%B8%D0%BA/4e8e01ba0aaf1c980294b72a] и получить скидку в 20% от их прайса.

Что такое "мэр" места - это тот человек который чаще всего регистрируется в этом месте. Часто мэры получают какие то преференции от заведения.

На территории России данный сервис пока развит слабо.

== AlterGeo

Роcсийский аналог Foursquare. Работает на всей территории России.

![Altergeo](/images/story/altergeo.png)

Сервис был запущен в 2007 году как сервис для определения своего местоположения на карте. На данный момент сервис предоставляет то же функционал что и Foursquare и немного больше. Сами заведения добавляются участниками сообщества. Так же администрация заведений может самостоятельно управлять своими рекламными компаниями.

Регулярно проводятся конкурсы и их победители получают подарки - от огромных скидок, до впролне реальной [турпоездки в европу][http://blog.altergeo.ru/?p=2116].

Так же как и в Foursquare у АльтерГео есть функция мэрства - но в этом сервисе она называется "Легенда". Легенда места, так же как и мэр в Foursquare, может получать бонусы от заведения.

== Google Latitude

Сервис геопозиционирования от Google.

![Google Latitude](/images/story/lat.png)

Третий сервис геопозиционирования. Обладает наименьшим функционалом. Прие его включении - на карте начинает отображаться положение устройства.

Так же существует функция "отметиться". Однако на территории России она не работает.

Однако у этого сервиса есть та функция, которая отсуцтвует у двух первых - есть возможность создать динамически изменяющуюся карту, на которой будет отмечено ваше положение. Эту карту можно использовать например в своём блоге.

Так же есть возможнось посмотреть историю своих перемещений по карте, и видеть собственных друзей, которы тоже пользуются Google Latitude.

= Промышленные сервисы

Сервисы для предприятий - отслеживание машин, контроль за тратой горючего, статистика эффективности использования транспорта.

С помощью данных систем можно существенно снизить расходы предприятия на транспорт, исключив, например, не целевое использование транспорта организации в личных целях.

Поскольку доcтупа к таким системам у меня нет - гугл помог мне найти демонстрационную карту одного из таких сервисов - [TrackRecord][http://online.tkrd.ru/stat/].

На карте обозначаются автомобили организации, оснащённые GPS-приёмниками, и можно получить любой отчёт о каждом автомобиле.

Принцип действия примерно такой же как и у трекинг-систем контроля доставки почты, только данные поступают не из конкретных точек где должен появиться объект, а в режиме реального времени.

= Сервисы контроля доступа

Это немного иной сервис чем Foursquare или TrackRecord.

На устройстве ставиться программа клиент, и при утере устройства, можно зарегистрироваться на специальном сайте, посмотреть где устройство находится и заблокировать к нему доступ.

Широкое распостранение данный способ использования геопозиционирования получил после увеличения доли смартфонов на рынке мобильных устройств.

Поскольку я не обладаю устройством данного класса - я просто расскажу о ПО которое предоставляет данный сервис.

== Norton Mobile Security Lite & Norton Anti-Theft Plug In

Антивирус от известного разработчика систем безопасности с плагином "Антивор".

![Norton Anti-Theft Plug In](https://lh6.ggpht.com/J6Y35-mAR75AKVGMM_i-mcRNt7qHtuhXxyS_qOfQko7XKdx4pYhfZnzALcNl2MJdGA)

Как видно из картинки - данный плагин позволяет определить местоположение утерянного устройства и отключить к нему доступ.

Вообще данный антивирус обладает довольно большим количеством плагинов, которые в большинстве своём совершенно бесплатны для использования.

== Lookout Mobile Security

<iframe width="560" height="315" src="http://www.youtube.com/embed/Jh7anr-Df9E" frameborder="0" allowfullscreen></iframe>

В бесплатной версии позволяет только найти утерянный телефон - с помощью карты и звукового сигнала. Платная версия позволяет заблокировать телефон и удалить всю конфиденциальную информацию с телефона, сделать полную резервную копию и восстановить на другой телефон.

== Kaspersky Mobile Security & Kaspersky Mobile Security Lite

Обе версии обладают возможностью нахождения телефона при его утере или краже. Платная версия может найти телефон даже если на нём сменили симкарту.

Есть ещё одна интересная программа, которая довольно оригинально использует геопозиционирование.

== Tasker

Это менеджер задач, автоматизирующий некоторые функции. Например, определив положение телефона рядом с домом или работой, эта программа способна включить wifi и подключиться к определённой сети.

Вообще, любая функция которая должна быть запущена в определённой точке планеты - может быть запущена.

= Послесловие

Вообще данные сервисы только набирают популярность. На данный момент геопозиционированием пользуются чаще организации, для таргетирования рекламы по месту проживания. Но уже есть сервисы которые реально позволяют получать выгоду от их использования конечным пользователям.