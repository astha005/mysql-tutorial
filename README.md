# mysql-tutorial
this is for my study
## Table definitions ##

### Table 1: CUSTOMER ###
```
create table sql3157590.CUSTOMER(customer_id integer primary key,first_name text,last_name text,email text,Adress text,city text,state text,zip text);

Insert into sql3157590.CUSTOMER values(1,"asdf","qwer","prats@gmail.com","215 abcd ave","san bruno","California",94066);
INSERT INTO sql3157590.CUSTOMER VALUES(2,"AST","MEHTA","ASTHA6@OUTLLOK.COM","CHINCHWAD","PUNE","MH",411019);
INSERT INTO sql3157590.CUSTOMER VALUES(3,"AKASH","PATEL","ANKY@YMAIL.COM","CANDNI CHOWK DELHI","AGRA","UP",23456);
```

### Table 2: ORDERS ###
```
CREATE TABLE sql3157590.ORDERS
(ORDER_ID INTEGER PRIMARY KEY,ORDER_DATE DATE,AMOUNT NUMERIC,
CONTRIBUTER_ID INTEGER,CAMPAIGN_ID INTEGER);

 SELECT * FROM sql3157590.ORDERS;
insert into sql3157590.ORDERS
values(1,CURRENT_TIMESTAMP,100,2,1);

insert into sql3157590.ORDERS
 (order_id,order_date,amount,contributer_id,campaign_id)
values
(2,CURRENT_TIMESTAMP,50,3,1); *
```
### Table 3: CAMPAIGN ###

```
create table sql3157590.CAMPAIGN (CAMPAIGN_ID INTEGER PRIMARY KEY,CAMPAIGN_NAME TEXT,CAMPAIGN_OWNER_ID INTEGER,AMOUNT_REQ INTEGER,ACTIVE INTEGER);

INSERT INTO sql3157590.CAMPAIGN VALUES(1,"SPEED_X",1,500,1);
```

### PRACTICE QUESTIONS ###

| S.No | Question | Query | 
|------|----------|-------|
|1.    |Find total active campaigns?| select count(*) from sql3157590.CAMPAIGN where active = 1
|2.    | Find total inactive campaigns?|
|3.    | Find total amount requested of all active campaigns?|
