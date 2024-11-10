 # <a name="up" />Тестирование Яндекс Маршрутов
# ♻️ Для проекта понадобится																						
# 1. Тестирование валидации полей в форме
# ![chrome_mOCe341B8Y](https://github.com/user-attachments/assets/e904fefc-a796-47a9-8684-001f47ec47e0)
# ![chrome_riMmtFqE4K](https://github.com/user-attachments/assets/364689f1-b799-4a7f-a661-301daa0f659e)
# ![chrome_8jVJXkv1Wy](https://github.com/user-attachments/assets/73950bfc-82fb-442b-809d-015310221ef0)
# ![chrome_xSDjSCQgJG](https://github.com/user-attachments/assets/d147b9e7-f7bc-48b3-89ec-71a9c80a92ae)
# ![chrome_CnnI8lYSxn](https://github.com/user-attachments/assets/f59d71cf-c3dd-4ee6-8b59-b7e86fd1d38b)
# ![chrome_Ood2OvmtIN](https://github.com/user-attachments/assets/6cafdbaf-8ddb-4cf8-9e69-aa1929af734a)
# ![chrome_FhPPac9n8T](https://github.com/user-attachments/assets/f8de192d-3a8f-4066-970b-797e9db46e52)
# ![chrome_Xn64XOQl8o](https://github.com/user-attachments/assets/067d777a-4a7d-4d5e-8303-e203d6ecc9fc)


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



# 2. Тестирование расчета стоимости и времени поездки на собственном автомобиле
Яндекс Маршруты рассчитывают время и стоимость поездки, в том числе на своем автомобиле. В требованиях есть таблицы средней скорости автомобиля и расстояний между адресами, на основе которых должен производиться расчет времени поездки. 
# По стоимости указано, что за 1 км. расход составляет 20 руб.
https://code.s3.yandex.net/qa/schemes/sprint01-project-005.png
https://code.s3.yandex.net/qa/schemes/sprint01-project-006.png
Тебе необходимо проверить, что приложение верно рассчитывает время и стоимость поездки для собственного автомобиля.
⚙ Время поездки рассчитывается по формуле t = S/V (где t - время поездки, S - расстояние, V - средняя скорость);
Стоимость поездки рассчитывается по формуле: *Р (итоговая) = S * P (где Р (итоговая) - стоимость поездки, S - расстояние, Р - стоимость 1 км.);*



Баг-репорты.

