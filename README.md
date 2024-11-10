 # <a name="up" />Тестирование Яндекс Маршрутов
# ♻️ Для проекта понадобится
# 1. Декомпозиция требований:
# ![yT8CwUxf49](https://github.com/user-attachments/assets/18f6cacc-69a8-4526-ae49-1f0e7f4ee766)
																						
# 2. Тестирование валидации полей в форме
В требованиях к Яндекс Маршрутам есть таблица с ограничениями на ввод в поля формы. 
https://code.s3.yandex.net/qa/schemes/sprint01-project-002.png
Валидация формы работает следующим образом: в случае корректного ввода появляется расчёт времени и стоимости поездки. В случае некорректного ввода появляется сообщение об ошибке. 
Тебе необходимо проверить, что в реализации применены все требования к полям и валидация проходит так, как задумано.
💡 Обрати внимание! В поля «Откуда» и «Куда» можно вводить только ограниченное количество адресов из таблицы в требованиях: Усачева, 3; Комсомольский проспект, 18; Зубовский бульвар, 37; М. Пироговская, 25; Хамовнический Вал, 34; Фрунзенская набережная, 46; 3-я Фрунзенская улица, 12. 
Используй перечисленные адреса в качестве тестовых данных в таблицах классов эквивалентности и граничных значений, а затем и в тест-кейсах.
В рамках задания тебе нужно:
Провести тест-анализ требований на валидацию полей. Если найдёшь серые зоны, обратись за разъяснением к преподавателю.
Создать набор тест-кейсов на проверку валидации полей формы Яндекс Маршрутов. Примени техники тест-дизайна: классы эквивалентности и граничные значения.
Протестировать валидацию полей и завести баг-репорты, если есть баги.
# ![bduiUBcXmf](https://github.com/user-attachments/assets/44429dfa-0fa4-4471-8ecf-970b50fa855e)

# ![dSuqBgCnfU](https://github.com/user-attachments/assets/89bc330d-d5a1-4fb6-8c6e-4260ce26c867)


# 3. Тестирование расчета стоимости и времени поездки на собственном автомобиле
Яндекс Маршруты рассчитывают время и стоимость поездки, в том числе на своем автомобиле. В требованиях есть таблицы средней скорости автомобиля и расстояний между адресами, на основе которых должен производиться расчет времени поездки. 
# По стоимости указано, что за 1 км. расход составляет 20 руб.
https://code.s3.yandex.net/qa/schemes/sprint01-project-005.png
https://code.s3.yandex.net/qa/schemes/sprint01-project-006.png
Тебе необходимо проверить, что приложение верно рассчитывает время и стоимость поездки для собственного автомобиля.
⚙ Время поездки рассчитывается по формуле t = S/V (где t - время поездки, S - расстояние, V - средняя скорость);
Стоимость поездки рассчитывается по формуле: *Р (итоговая) = S * P (где Р (итоговая) - стоимость поездки, S - расстояние, Р - стоимость 1 км.);*
Важно! Средняя скорость для расчета берется по времени начала поездки.
В рамках задания тебе нужно:
Провести тест-анализ требований расчёта времени и стоимости маршрута на собственном автомобиле. Если найдёшь серые зоны, обратись за разъяснением к преподавателю.
Применить технику тест-дизайна «Классы эквивалентности» и создать набор тест-кейсов на проверку правильности расчета времени и стоимости поездки на собственном автомобиле.
💡 При составлении тест-кейсов используй значения только из колонки «Тестовые данные внутри класса» — для сдачи проекта этого набора тестов будет достаточно.
Протестировать расчеты и завести баг-репорты, если есть баги.
На проверку ревьюеру ты сдаешь: 
Таблицу с классами эквивалентности.
Набор тест-кейсов к расчетам.
Баг-репорты.
Работа выполняется в одной «Рабочей таблице», в которой есть отдельные листы на каждый этап.# -
