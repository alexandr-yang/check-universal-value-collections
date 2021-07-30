# Набор утверждений для проверки универсальных коллекций

Плагин для фреймворка [Vanessa-ADD](https://github.com/vanessa-opensource/add).

## Установка

## Подключение

```
юТест_УтвержденияУК = юТест.Плагин("ПроверкаУниверсальныхКоллекций");
```

## Пример использования

```
ОжидаемыйРезультат = Новый Структура;
ОжидаемыйРезультат.Вставить("Ключ1", 1);
ОжидаемыйРезультат.Вставить("Ключ2", "Значение2");

Результат = ТестовыйМодуль.ПолучитьСтруктуруДанных();

юТест_УтвержденияУК.СтруктурыИдентичны(
    Результат, ОжидаемыйРезультат,
    "Результат не соответствует ожидаемому"
);
```

## Описание методов

### Процедуры работы с массивами и фиксироваными массивами 
* МассивыИдентичны
* МассивыНеИдентичны
* МассивПустой
* МассивНеПустой
* МассивСодержит
* МассивНеСодержит

### Процедуры работы со структурами и фиксироваными структурами
* СтруктурыИдентичны
* СтруктурыНеИдентичны
* СтруктураПустая
* СтруктураНеПустая
* СтруктураСодержит
* СтруктураНеСодержит

### Процедуры работы с соответствиями и фиксироваными соответствиями
* СоответствияИдентичны
* СоответствияНеИдентичны
* СоответствиеПустое
* СоответствиеНеПустое
* СоответствиеСодержит
* СоответствиеНеСодержит

### Процедуры работы со списками значений
* СпискиЗначенийИдентичны
* СпискиЗначенийНеИдентичны
* СписокЗначенийПустой
* СписокЗначенийНеПустой
* СписокЗначенийСодержит
* СписокЗначенийНеСодержит
