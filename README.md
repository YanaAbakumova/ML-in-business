# Предсказание оттока клиентов

Использован датасет https://www.kaggle.com/blastchar/telco-customer-churn

#### Описание датасета:

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The data set includes information about:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

#### Задача:

создать приложение, которое будет выдавать ответ, склонен ли запрашиваемый покупатель (покупатели) уйти в отток. 

Подразумевается, что можно ввести неправильные данные или незнакомый для предобученной модели категориальный признак, задача по этим данным сделать прогноз. 

Обработка данных происходит только в рамках пайплайна. Отсутствующие/ошибочные данные в количественных признаках заполняются медианой, в категориальных - модой  
