# parser-hh
Получение данных о вакансиях с помощью API hh.ru

Документацию по API hh.ru можно посмотреть [здесь](https://github.com/hhru/api) 

Токен доступа из кода был удален, при запуске будет необходимо вставить полученный код для вашего приложения

При сборе данных собираются такие данные как:
  - название вакансии
  - название компании
  - местоположение
  - зарплата(делится на две колонки)
  - описание вакансии

Данные собираются по 29 различным параметрам, которые представляют собой названия вакансий и области работы. При изменении количества параметров необходимо корректировать соответствующее число и циклы в коде.

Собственно итоговая табличку с данными по собираемыми мной вакансиям тоже прикреплена. Предобработка данных в коде есть, выбросы обрабатывались уже в экселе, ручками

Мноц данные собирались для дата анализа, хз для чего еще они могут кому-то могут быть нужны. БЗВ, они есть
