# Задание по изучению инструмента разработчика Chrome-DevTools

## Панель Elements 
 1. Зайти на страничку https://itcareer.pythonanywhere.com/
     и открыть Chrome DevTools
 2. Зайти в панель Elements.
 3. Найти инспектором кнопку Submit и выровнять слово Submit по центру
 4. Включить режим мобильного деввайса (Device Mode)
 5. Выставить Dimensions: Responsive 
 6. Выбрать Responsive - Mobile
 7. Продемонстрировать работу дизайна Responsive
 8. Выставить Dimensions: Adaptive (select device).
 9. Создать свой девайс.
 10. Выставить Throttling low-end mobile
 11. Обновить страницу
 12. Перевести в ландшафтные режим.
 13. Выключить Device Mode
      
## Панель Console 
 1. Зайти на сайт https://www.ozon.ru/ и открыть панель Console.
 2. Найти сообщения Error в логах
 3. Сохранить 2 сообщения лога как файл на компьютер.
 4. Найти 1 сообщение verbose
 5. Пролистать логи Warnings, Info, User Messages.
 6. Открыть вкладку Sources.
 7. Открыть файл Index
 8. Открыть вкладку Network
 
## Работа с вкладкой Headers and Preview
 1. В урле отправить http://162.55.220.72:5005/object_info_3?age=32&salary=1000&name=name
 2. Найти лог request/responce  
 3. Открыть вкладку Headers
 4. Просмотреть General, Response Headers, Request Headers
 5. Найти и скопировать в новый текстовый файл header - User-Agent.
 6. Открыть вкладку Preview
 7. Развернуть все уровни вложенности JSON.
 8. Открыть вкладку Application.
 9. Развернуть все Storage в левом столбце.
 10. Зайти в Cache Storage и Application Cache
 11. Там везде будет пусто.
 
## Вкладка LightHouse
 1. Открыть сайт https://www.greenvpeace.org/
 2. Откройте вкладку LightHouse
 3. Нажмите Generate report
 
## Скриншоты в DevTools 
 1. Установить в браузер бесплатный AdBlocker
 2. Установить в браузер Json Viewer
 3. Зайти на сайт https://ksendzov.com
 4. Сделать и сохранить скриншот видимой части страницы сайта.
 5. Сделать и сохранить скриншот всего сайта.
 
## Работа с Google Maps и параметров Locations.
 1. Изменить локацию GPS. Продемонстрировать на сайте Гугл карт.
 2. Изменить локацию GPS второй раз. Продемонстрировать на сайте Гугл карт.
 
## Подмена User-Agent
 1. Найти интерфейс для изменения User-Agent.
 2. Подставить другой User-Agent. 
 3. Отправить запрос на http://162.55.220.72:5005/object_info_3?age=32&salary=1000&name=name
 4. Проверить изменился ли ваш нативный User-Agent на новый, подставленный.
 5. Создать свой юзер агент.
 6. Повторить пункты 3, 4.
 
## Изменения параметров Throtling для http://next-idea.ru/
 1. Найти интерфейс для изменения/добавления параметров Throttling.
 2. Создать свои параметры плохого соединения и проверить как будет загружаться страница.
