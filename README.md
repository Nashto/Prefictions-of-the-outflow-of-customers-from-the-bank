# Prefictions-of-the-outflow-of-customers-from-the-bank
Работа прогнозирует, уёдет ли клиент из Банка в ближайшее время или нет

Описание проекта
Из Банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. В работе предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
Необходимо построить модель с предельно большим значением F1-меры. Чтобы проект считать успешным, нужно довести метрику до 0.59. 


Описание данных
•	RowNumber — индекс строки в данных
•	CustomerId — уникальный идентификатор клиента
•	Surname — фамилия
•	CreditScore — кредитный рейтинг
•	Geography — страна проживания
•	Gender — пол
•	Age — возраст
•	Tenure — сколько лет человек является клиентом банка
•	Balance — баланс на счёте
•	NumOfProducts — количество продуктов банка, используемых клиентом
•	HasCrCard — наличие кредитной карты
•	IsActiveMember — активность клиента
•	EstimatedSalary — предполагаемая зарплата

Целевой признак
•	Exited — факт ухода клиента
