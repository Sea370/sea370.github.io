sPutnik  - мобильное приложение разработанное в рамках хакатона Navihack - 2018.

Приложение предназначено для автоматизации процессов составления маршрутов.

Приложение может быть полезно менеджерам для планирования встреч в ходе бизнес-поездок, 
экспедиторским службам и службам доставки и т.п.

Приложение поддерживает следующие функции:
* Просмотр имеющихся маршрутов
* Добавление нового маршрута по списку имеющихся навиадресов объектов
* Автоматическое определение названий и адресов объектов, редактирование и добавление дополнительных контактных данных и взаимодействие с ними из приложеня.
* После задания настроек можно провести построение маршрута.
* Cначала выбирается начальная точка, после этого остальные точки распределяются от неё таким образом, чтобы каждая следующая (из тех, которые ещё не были посещены) оказывалась ближайшей к предыдущей.
* На основании заданных настроек, расчитывается ориентировочное время посещения каждой точки и ориентировочные транспортные расходы.
* Вывод данных маршрута на печать или сохранение в PDF файле.

При разработке приложения были использованы следующие библиотеки и API:
* Naviaddress API (считывание данных).
* Функция Google API для определения расстояния между объектами.
* CSS-фреймворк Ratchet для разработки мобильных приложений.
* Библиотека Moment.js для работы с временными интервалами.

Рабочая версия приложения доступна по адресу: http://sea370.github.io.

(c) С. Ананьев, 2018
