# Customer-Exited
Отток клиентов

## Описание проекта

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Построить модель с предельно большим значением F1-меры. 
Измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

### Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

![alt text](https://webimpulse.net/wp-content/uploads/2018/05/predotvrashenie-poter.jpg
)

### Инструкция по выполнению проекта

Загрузить и подготовить данные. 
Исследовать баланс классов, обучить модель без учёта дисбаланса. Выводы.
Улучшить качество модели, учитывая дисбаланс классов. Обучить разные модели и найдите лучшую. Выводы.
Провести финальное тестирование.

### Описание данных
Данные находятся в файле Churn.csv (англ. «отток клиентов»).

#### Признаки
##### RowNumber — индекс строки в данных
##### CustomerId — уникальный идентификатор клиента
##### Surname — фамилия
##### CreditScore — кредитный рейтинг
##### Geography — страна проживания
##### Gender — пол
##### Age — возраст
##### Tenure — количество недвижимости у клиента
##### Balance — баланс на счёте
##### NumOfProducts — количество продуктов банка, используемых клиентом
##### HasCrCard — наличие кредитной карты
##### IsActiveMember — активность клиента
##### EstimatedSalary — предполагаемая зарплата
#### Целевой признак
##### Exited — факт ухода клиента
