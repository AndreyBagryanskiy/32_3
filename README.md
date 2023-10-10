Задача 3. Модель данных компании на Protobuf

Что нужно сделать
Создайте модель данных для информации о предприятии. Обязательные поля: год основания (целое 32-битное число), 
юридический адрес (строка) и название (строка). Опциональные поля: род деятельности (строка), 
осуществление внешнеэкономической деятельности (булевый тип)

Опишите модель на языке proto2 и сохраните её в отдельный документ с расширением proto. 
Затем на основе созданного документа сгенерируйте C++-код с помощью компилятора protoc.

Что оценивается
Валидность созданной модели на языке proto2 и её успешное преобразование в C++-код.
