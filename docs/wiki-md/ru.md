
# Cpp.Comet - Документация

  * Если вы хотите понять зачем вам нужен комет сервер то прочтите [вводную статью](/docs/wiki-md/comet/introduction-to-comet.md)
  * Начать освоение API рекомендуется с изучения [CometQL](/docs/wiki-md/comet/CometQL.md) и [JavaScript API](/docs/wiki-md/comet/javascript_api.md)


# Актуальные статьи

  * [Введение](/docs/wiki-md/comet/introduction-to-comet.md) - Описание технологии comet, возможностей, сферы применения. Как работают push уведомления.
  * [Описание CometQL](/docs/wiki-md/comet/CometQL.md) - серверное api для работы с комет сервером
  * [Описание JavaScript API](/docs/wiki-md/comet/javascript_api.md)  - клиентское api для работы с комет сервером
  * [Online demo отправки сообщений](/docs/wiki-md/comet/faq/send-message-to-pipe.md) - Online demo и пример кода отправки сообщений в канал.
  * [Пример Realtime чата](/docs/wiki-md/comet/simple-chat-example.md) - Учебный пример Realtime чата
  * [Готовый чат на JavaScript для сайта - chat плагин](/docs/wiki-md/comet/simple-chat-plugin.md) - Подключаемый плагин простого чата
  * [Как сделать чат с авторизацией](/docs/wiki-md/comet/chat-with-authorization.md) - Как сделать простой php chat на сайте, урок с примерами и online demo
  * [Как сделать Realtime уведомления на сайте](http://dimasudarkin.ru/%D0%BA%D0%B0%D0%BA-%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C-realtime-%D1%83%D0%B2%D0%B5%D0%B4%D0%BE%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BD%D0%B0-%D1%81%D0%B0%D0%B9%D1%82%D0%B5/) - Реализация отправки уведомлений авторизованным на комет сервере пользователям по их идентификатору.
  * [Как определить, онлайн пользователь или нет](http://dimasudarkin.ru/%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C-%D0%B8%D0%BB%D0%B8-%D0%BD%D0%B5%D1%82-php/) - Пример определения онлайн пользователь или нет на php
  * [Star.Comet-Chat](/docs/wiki-md/comet/star-comet-chat.md) - Плагин чата для личной переписки пользователей между собой.
  * [Зарезервированные имена каналов](/docs/wiki-md/comet/javascript_api/pipe-types.md) - описание каналов с особыми свойствами
  * [Пример отправки сообщения из bash скрипта](/docs/wiki-md/comet/cometql-bash-example.md)
  * [Коды ошибок в CometQL](/docs/wiki-md/comet/cometql/error.md) - Коды ошибок которые можно получить при работе с CometQL API
  * [Публичный идентификатор разработчика](/docs/wiki-md/comet/dev_id.md) - Что такое "Публичный идентификатор разработчика" и "Секретный ключ разработчика"
  * [Авторизация пользователей](/docs/wiki-md/comet/authentication.md) - Описание механизма на авторизация пользователей на комет сервере 
  * [Пример чата на php](https://github.com/CppComet/php-chat-example)
  * [Использование comet сервера для реализации простого чата](https://habrahabr.ru/company/comet-server/blog/273573/)
  * [Создаём простой Realtime чат](https://habrahabr.ru/company/comet-server/blog/272817/)


# Администрирование комет сервера

  * [Установка](/docs/wiki-md/comet/building-from-source.md) - Инструкция по сборке и установке комет сервера на свой сервер
  * [Как провести нагрузочное тестирование](/docs/wiki-md/comet/load-testing.md) - Как провести нагрузочное тестирование сервера с помощью tsung
  * [Отчёт о нагрузке в 64000 онлайн](/docs/wiki-md/comet/load-testing-result.md) - Результаты нагрузочного тестирования

# Техническая поддержка и ответы на вопросы

Вопросы по работе с проектом можно [задавать на форуме](http://community.comet-server.com) на них будет отвечать техподдержка и возможно другие участники сообщества.


___
Если у вас не личный вопрос, а вопрос который возможно может заинтересовать и других пользователей то лучше спросить [на форуме сообщества](http://community.comet-server.com) так как в таком случаи и другие люди смогут увидеть ответ. Или возможно даже вам ответит кто то быстрее чем в техподдержке
___


# Планы по развитию проекта

О том какие улучшения запланированы, а какие уже внедряются можно посмотреть на [этой странице](https://github.com/CppComet/comet-server/projects/1)
Если есть какие то предложения, вопросы, пожелания или просьбы по добавлению новых функций то можно [здесь создать issue](https://github.com/CppComet/comet-server/issues) или написать в техподдержку после регистрации.

# Вопросы и ответы
  * [Что лучше Long Polling или WebSockets?](/docs/wiki-md/comet/faq/websockets-vs-longpolling.md)
  * [Как отправить сообщение в канал?](/docs/wiki-md/comet/faq/send-message-to-pipe.md)
  * [Как принять сообщение из канала в JavaScript?](/docs/wiki-md/comet/faq/js-api-subscription.md)
  * [Какие браузеры поддерживаются?](/docs/wiki-md/comet/faq/what-browsers-are-supported.md)
  * [Почему реализовывать comet server на php не так эффективно?](/docs/wiki-md/comet/faq/use-php-as-comet-server.md)
  * [Движение одной переменной от клиента к серверу и от сервера к клиенту](/docs/wiki-md/comet/faq/movement-of-one-variable.md)
  * [Почему скрипт работает на локальной машине и не работает на хостинге? ](/docs/wiki-md/comet/testhosting.md)
  * [Что такое и зачем нужен "Публичный идентификатор разработчика" и "Секретный ключ разработчика"?](/docs/wiki-md/comet/faq/public_key.md)
  * [Как отправить сообщение в произвольный канал и как его потом получить на другой странице?](/docs/wiki-md/comet/faq/send-message-to-pipe.md)
  * [Как реализовать механизм отслеживания вхождения пользователей на сайт. То есть список посетителей обновляющийся на "лету"?](/docs/wiki-md/comet/faq/realtime-users-list.md) 
  * [Может ли кто то посторонний получать сообщение из каналов?](/docs/wiki-md/comet/faq/access-to-channels-for-outsiders.md)
  * [Надо ли экономить количество каналов?](/docs/wiki-md/comet/faq/max-numbers-of-pipes.md)
# Список готовых решений использующих Star.Comet
 
  * [Плагин личной переписки между пользователями](/docs/wiki-md/comet/star-comet-chat.md)
  * [Плагин уведомлений для MogutaCMS](/docs/wiki-md/user/app/mogutacms.md)
  * [Плагин уведомлений для MODX messenger](/docs/wiki-md/user/app/modx-messenger.md)


___
Если вы создали какое то приложение или плагин для CMS использующий этот комет сервис и планируете это приложение продавать или раздаёте бесплатно то напишите об этом по адресу app@comet-server.ru для того чтоб информация о вашем приложении была добавлена в [специальный раздел](/docs/wiki-md/user/app.md) на этом сайте.
Возможно это привлечёт к вам несколько дополнительных пользователей.
___

 
[Список готовых решений использующих Star.Comet](/docs/wiki-md/user/app.md)
 
# Другие языки # 

Эта страница на [Английском языке](/docs/wiki-md/en.md)
