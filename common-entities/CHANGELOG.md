## 1.2 (10.11.2022)

----

### Release Highlight

**Первый changelog** 🎉

Расширен класс `ExternalLink`. Переопределены методы `equals` и `hashCode`.
Теперь мы можем сравнивать два экземпляра `ExternalLink` по-содержимому пользуясь методом equals.
Так же теперь мы можем использовать `HashSet`, для того чтобы собирать уникальную коллекцию.

Сравнение происходит по полям `id` и `type`

### Features

- Переопределены методы `equals` и `hashCode` для класса `ExternalLink`

### Docs

- Добавлена документация класса `QuarterRange`

## 1.1.1 (15.08.2022)

----

### Release Highlight

Теперь время и дата удаления для объектов `BaseDeleteEntity` сохраняется в поле `deletedAt`

Исправления работы класса утилиты `QuarterRange`. Метод `end` возвращал время начала дня, а требовалось время окончания
дня

### Features

- Добавлено сохранение времени удаления для `BaseDeleteEntity`

### Fixes

- Исправления метода end класса `QuarterRange`
- Методы работы с `DateTimeObject` в `DateTimeObjectCriteria` помечены как `Deprecated`. При работе они вызывают ошибки

### Docs

- Расширил описание методов `DateTimeObjectCriteria`, указал какие ошибки они вызывают
