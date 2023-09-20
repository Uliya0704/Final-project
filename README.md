ИТОГОВЫЙ ПРОЕКТ ПО АВТОМАТИЗАЦИИ ТЕСТИРОВАНИЯ (PJ-04)

В ходе выполнения итогового проекта требуется протестировать авторизацию интерфейса в личном кабинете Ростелеком Информационные Технологии.

Объект тестирования: https://b2c.passport.rt.ru .

Заказчик передал вам следующее задание:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести ускоренное тестирование продукта (не менее 20 автотестов). Оформить обнаруженные дефекты. 
Результат работы:
Проведено ручное и пошаговое тестирование с использованием PyTest и Selenium.
Для составления и написания тест-кейсов применяются методики тест-дизайна: классы эквивалентности, анализ граничных результатов, предугадывание ошибок.
Тестирование требований, Тест-кейсы и баг-отчеты в гугл-таблице: https://docs.google.com/spreadsheets/d/1z7Jac-XbCARHCpdLHsdN6U_ZMly_EbLHoplIP_2O8R8/edit?usp=sharing
Комментарий по автотестам:

В файле base_data.py отображаются базовые классы, процедуры, функции и локаторы для автотестов.

В файле settings.py — регистрационные данные для авторизации положительных тестов.

В файле test_task_28_1_finality.py — автотесты. 
Тесты помечены номером, который соответствует номеру тест-кейсам 

Запуск автотестов (драйвер в одной настройке с тест-скриптом)

python -m pytest -v --driver Chrome --driver-path chromedriver.exe test_task_28_1_finality.py
