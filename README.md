# WildberriesInfo
Пояснения к файлу с отчетами Wildberries

Wildberries гарантирует хранение данных не более 90 дней от даты заказа. С каждым запуском скрипт накапливает данные, для **Заказы, Продажи, Отчет по реализации**.<br/>

По умолчению выгружаются все поля, которые можно получить согласно официальной документации [API Wildberries](https://openapi.wb.ru/#tag/Statistika).

## Настройка и подключение
* Примите права на почте;
* Обновите страницу, у вас появится меню:
![image](https://user-images.githubusercontent.com/72359732/235485033-32e37c7d-cdcb-4ad3-abe7-f02eae1d8e35.png)

Нажмите **Wildberries > Поставки**. Скрипт попросит при первом запуске авторизацию. Следуйте инструкции:
[Как авторизовать скрипт](https://dzen.ru/media/excelifehack/kak-avtorizovat-skript-v-google-tablicah-61a943694333203e458eb600).


## Заменить или обновить ключ API
_Для выгрузки данных используется ключ [API тип Статистика](https://seller.wildberries.ru/login/ru/?redirect_url=/supplier-settings/access-to-new-api)_
* Файл в котором уже устновлен ваш ключ делать ничего не нужно;
* Файл без установленного ключа (или копия), нажмите: **🔑 Ключ API (Статистика)**, в открывшееся окно для ввода ключа вставьте ключ из Личного кабинета;
* Нужно поменять ключ в этом же файле, нажмите: **❌ Удалить API (Статистика)**, после появления сообщении об успешном удалении предыдущего ключа, см. выше.


## Установка триггеров
_Для установки выгрузки по расписанию, нажмите: **Wildberries > Настройки > Триггеры**_

![image](https://user-images.githubusercontent.com/72359732/235483887-5ca6b64e-9cda-4bf0-8edd-d0aa35bd2904.png)

Через меню можно поставить триггеры для запуска отчетов по расписанию, выборочно или все сразу.

## Типы выгрузки
* Выгрузка из меню: **Wildberries > кнопка (Поставки, Склад, Заказы, Продажи, Отчет по реализации)**;
* Выгрузка по расписанию: **триггеры**;
* Выгрузка с: ввести начальную дату в поле на листе **Поддержка**.

После приемки работы на **Kwork** все вопросы в поддержку.
