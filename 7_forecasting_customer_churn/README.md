# Отток клиентов


**Нам известно:** Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Цель проекта:** Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.

**Задачи проекта:** Построить модель с предельно большим значением *F1*-меры. Чтобы считать проект успешным, нам нужно довести метрику до 0.59. Будем проводить проверку *F1*-меры на тестовой выборке.


*Дополнительно измерим AUC-ROC, сравнивая её значение с F1-мерой.*


# Описание данных


**Признаки:**

    RowNumber — индекс строки в данных
    CustomerId — уникальный идентификатор клиента
    Surname — фамилия
    CreditScore — кредитный рейтинг
    Geography — страна проживания
    Gender — пол
    Age — возраст
    Tenure — сколько лет человек является клиентом банка
    Balance — баланс на счёте
    NumOfProducts — количество продуктов банка, используемых клиентом
    HasCrCard — наличие кредитной карты
    IsActiveMember — активность клиента
    EstimatedSalary — предполагаемая зарплата
    
**Целевой признак:**

    Exited — факт ухода клиента
    
    
Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)


# Используемые библиотеки

pandas, matplotlib, scikit-learn

# Статус проекта 

Завершен
