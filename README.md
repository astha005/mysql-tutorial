# mysql-tutorial
this is for my study
## Table definitions ##

create table sql3157590.CUSTOMER(customer_id integer primary key,first_name text,last_name text,email text,Adress text,city text,state text,zip text);

Insert into sql3157590.CUSTOMER values(1,"prateek","chaturvedi","prats@gmail.com","215 boardwalk ave","san bruno","California",94066);
INSERT INTO sql3157590.CUSTOMER VALUES(2,"ASTHA","MEHTA","ASTHA6@OUTLLOK.COM","EMPIRE ESTATE CHINCHWAD","PUNE","MH",411019);
INSERT INTO sql3157590.CUSTOMER VALUES(3,"AKASH","PATEL","ANKY@YMAIL.COM","CANDNI CHOWK DELHI","AGRA","UP",23456);

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

create table sql3157590.CAMPAIGN (CAMPAIGN_ID INTEGER PRIMARY KEY,CAMPAIGN_NAME TEXT,CAMPAIGN_OWNER_ID INTEGER,AMOUNT_REQ INTEGER,ACTIVE INTEGER);

INSERT INTO sql3157590.CAMPAIGN VALUES(1,"SPEED_X",1,500,1);
