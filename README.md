# mysql-tutorial
this is for my study
## Table definitions ##


*CREATE TABLE sql3157590.ORDERS
(ORDER_ID INTEGER PRIMARY KEY,ORDER_DATE DATE,AMOUNT NUMERIC,
CONTRIBUTER_ID INTEGER,CAMPAIGN_ID INTEGER);*

Insertions:
* SELECT * FROM sql3157590.ORDERS;
insert into sql3157590.ORDERS
values(1,CURRENT_TIMESTAMP,100,2,1);

insert into sql3157590.ORDERS
 (order_id,order_date,amount,contributer_id,campaign_id)
values
(2,CURRENT_TIMESTAMP,50,3,1); *
