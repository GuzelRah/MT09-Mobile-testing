# Отчет о тестировании нативного приложения "Tutu"
Apple iPhone 14 Pro Max (Дисплей: 6.7" OLED - 1290 x 2796; Чип: Apple A16 Bionic;
Батарея: 4323 мАч; OS: iOS 16.5)

№|Тест|Pass/Fail|Результат|
|:--|:--|:--|:--|
||**Тестирование функциональности**|||
|1|Установка приложения Tutu  с App Store|Pass|Приложение устанавливается на телефон|
|2|Удаление приложения Tutu  с App Store|Pass|Приложение удаляется с телефона|
|3|Авторизация в приложении - регистрация|Pass|Авторизация успешна|
|4|Авторизация в приложении - вход зарегистрированного пользователя|Pass|Авторизация успешна|
|5|Авторизация в приложении - вход через  ВК, Одноклассники, Google, Apple ID|Pass|Авторизация успешна|
|6|Онбординг новых пользователей|Pass|Происходит знакомство нового пользователя с функционалом|
|7|Навигация между разделами приложения|Pass|Навигация между разделами происходит  легко и понятно|
|8|Редактирование данных в профиле пользователя|Pass|Профиль редактируется|
|9|Проверка поиска билетов/номеров по разным направлениям|Pass|Поиск билетов и номеров успешен|
|10|Проверка возможности изменения обложек|Pass|Обложки изменяются|
|11|Проверка оплаты|Pass|Оплата проходит|
|12|Проверка фильтров|Pass|Билеты/номера фильтруются в соответствии с параметрами|
|13|Проверка сортировки |Pass|Билеты/номера сортируются в соответствии с параметрами|
|14|Проверка применения промокодов и бонусов|Pass|Промокоды применяются|
|15|Проверка запуска приложения (Splash Screen)|Pass|При запуске открывается на несколько секунд экран заставки|
|16|Проверка работы чата с поддержкой|Pass|Чат отвечает/сообщения в чат отправляются|
|17|Проверка возможности бронирования билетов|Pass|Бронирование осуществляется|
|18|Проверка возможности добавления данных пассажиров в раздел "Пассажиры"|Fail|Добавление нового пассажира не произошло|
|19|Проверка корректного отображения ошибок|Pass|Ошибки отображаются корректно|
|20|Проверка скролл/свайп элементов экрана|Pass|Приложение плавно прокручивается, все данные при этом корректно отображаются|
|21|Проверка сворачивание/разворачивание приложения|Pass|Приложение сворачивается и разворачивается|
|22|Проверка разных типы подключений (2G/3G/LTE/Wi-Fi)|Pass|Приложение при смене интернета работает стабильно|
|23|Проверка смены языка приложения|Fail|При переходе в настройки не дает сменить язык|
||**Тестирование совместимости**|||
|24|Проверка работы приложения при блокировке девайса|Pass|Приблокировке приложениеработает в фоновом режиме|
|25|Проверка работы приложения при включении/выключении телефона в авиарежим|Pass|При переходе в режим самолета приложение работает ожидаемо|
|26|Проверка работы приложения при включении/выключении геолокации|Pass|Приложение не находит метоположение при отключении геолокации|
|27|Проверка поиска билетов/номеров при блокировке экрана|Pass|При блокировке поиск билетов осущесивляется|
|28|Проверка не происходит ли выход из профиля при работе приложения в фоновом режиме |Pass|Вылогирование не происходит|
|29|Проверка соблюдения приложением политики обработки персональных данных|Pass|Приложение открывает документ о перс данных |
|30|Проверка работы приложения при прерывании звонком/сообщением|Pass|Приложение работает стабильно|
|31|Проверка работы приложения при подключении к телефону внешних устройств|Pass|Приложение работает стабильно|
||**Тестирование  безопасности**|Pass||
|32|Пароль  при авторизации  скрывается астерисками|Pass|Данные пароля скрыты|
||**Тестирование удобства использования**|||
|33|Проверка корректности заголовки экранов|Pass|Заголоки отображаются корректно|
|34|Проверка унификации дизайна|Pass|Дизайн унифицирован|
|35|Проверка правильности написания текста|Pass|Тексты написаны правильно|
