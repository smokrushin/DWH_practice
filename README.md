## DWH_practice

[Ссылка](https://drive.google.com/file/d/1wvevHHYRP3NBeIWdnFUKz8l_AZyT5htr/view?usp=sharing) на диаграммы в draw.io

В качестве демонстративного примера используется процесс оформления заказа в интернет-магазине.
В рамках бизнес-процесса пользователь (**customer**), указывающий для доставки свой адрес (**customer_address**) совершает заказ (**order**). В заказе содержатся товары (**product**), которые в свою очередь попадают в какую-то подкатегорию (**subcategory**) и более крупную категорию (**category**)

Сущности обладают следующими атрибутами:

**Customer**
-	Идентификатор пользователя
-	ФИО
-	Пол
-	Возрастная категория

**Customer_address**
-	Идентификатор адреса пользователя
-	Почтовый индекс
-	Город
-	Адрес

**Order**
-	дата и время заказа
-	идентификатор товара в заказе
-	количество товара с одним идентификатором
-	размер скидки
-	итоговая сумма в заказе по товару с одним идентификатором

**Product**
-	идентификатор товара
-	название товара
-	описание товара
-	цена товара
-	бренд
-	цвет
-	актуальная версия по SCD2

**Subcategory**
-	Идентификатор подкатегории
-	Название подкатегории
-	Описание подкатегории

**Category**
-	Идентификатор категории
-	Название категории
-	Описание категории 


### Скриншоты модели данных для разных методологий:

**Dimensional modelling**

![dimensional_modelling](https://github.com/smokrushin/DWH_practice/blob/main/Dimensional%20modelling.png)

**Data vault**

![data_vault](https://github.com/smokrushin/DWH_practice/blob/main/Data%20Vault.png)

**Anchor modeling**

![anchor](https://github.com/smokrushin/DWH_practice/blob/main/Anchor.png)
