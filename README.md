# Loginom Scoring Engine Kit

* Версия 1.0.1
* Проверено: Все редакции Loginom 6.3.2

В компонентах библиотеки **Loginom Scoring Engine Kit** реализован алгоритм расчёта скорингового балла по готовой скоринговой карте. Возможен расчёт для карт двух форматов:

* с преобразованием всех атрибутов в категориальные;
* с преобразованием только непрерывных атрибутов в категориальные.

Кроме того реализовано формирование списка причин отказа.

## Установка

1. Перейдите в рабочий каталог приложения-клиента Loginom Studio  (по умолчанию это `C:\ProgramData\...\Loginom 6\Server\UserStorage\<Логин пользователя>`) или назначьте каталог на локальном диске в случае Loginom CE.
2. Создайте каталог **credit_scoring_pack**.
3. Распакуйте архив **scoring_engine_kit.zip** и поместите все файлы из архива в каталог **credit_scoring_pack** так, как они лежали в архиве.

## Требования

Для работы библиотеки **Loginom Scoring Engine Kit** необходимо:

* Клиент доступа к Loginom Studio или любая локальная редакция Loginom. Версия не ниже 6.3.2

## Список компонентов

* Преобразование атрибутов 1
* Преобразование атрибутов 2
* Скоринговая карта
* Причины отказа

Подробное описание компонентов доступно в [документации](docs/loginom-scoring-engine-kit.pdf).
