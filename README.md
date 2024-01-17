# Foodtechlab Backend Libraries

Библиотеки для бекенд разработчика компании Foodtechlab. 

## Основные

### api-exception-handler
Библиотека для перехвата ошибок в передаче их через RESTFul API в формате компании  

[Документация](api-exception-handler/README.md)

### common-entities
Содержит в себе множество базовых общих бизнес сущностей, таких как номер или координаты

[Документация](common-entities/README.md)

### i18n
Состоит из набора утилит для локализации приложений

[Документация](i18n/README.md)

### microservice-integration
Пак из утилит для обмена сообщениями между сервисами

[Документация](microservice-integration/README.md)

### microservice-integration
Пак из утилит для обмена сообщениями между сервисами

[Документация](microservice-integration/README.md)


## Экспериментальные

Данные библиотеке ещё в активной стадии проектирования

### domain-beans
При подключении автоматически формирует из UseCase и EventHandler бины

[Документация](domain-beans/README.md)

### exception-converter
При общении между микросервисами используя API умеет запрос с ошибкой обработать и выкинуть как исключение.
Иными словами делает работу с исключениями при интеграции с разными сервисами нативной

[Документация](exception-converter/README.md)


## Устаревшие


----

На данный момент библиотеки никто не поддерживает и не использует

### tests-helper
Набор классов для тестирования

[Документация](api-exception-handler/README.md)

### data-replication
Помогает распределять данные между микросервисами

[Документация](api-exception-handler/README.md)


## Таблица совместимости
Для переезда со старых версий библиотек на новый воспользуйтесь этой инструкцией

[Таблица совместимости](CAPTABLE.md)

## Правила изменения
Если у вам нужно добавить функционал или исправить ошибку, вы можете сделать форк и последующий Pull Request.
Наша команда рассмотрит ваше предложение и внесёт в следующие релизы.


## Лицензия
Лицензия MIT https://opensource.org/license/mit/

Лицензия MIT позволяет другим лицам свободно использовать, изменять и распространять ваше программное обеспечение при условии, что они сохранят исходное уведомление об авторских правах и лицензии.
