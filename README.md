# training_teacher
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.

Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Описание признаков в датасете:
Признаки:
RowNumber — индекс строки в данных;
CustomerId — уникальный идентификатор клиента;
Surname — фамилия;
CreditScore — кредитный рейтинг;
Geography — страна проживания;
Gender — пол;
Age — возраст;
Tenure — сколько лет человек является клиентом банка;
Balance — баланс на счёте;
NumOfProducts — количество продуктов банка, используемых клиентом;
HasCrCard — наличие кредитной карты;
IsActiveMember — активность клиента;
EstimatedSalary — предполагаемая зарплата;

Целевой признак:
Exited — факт ухода клиента.
