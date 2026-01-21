**1.** Create a table st\_info with attributes prn, name,m1,m2,m3

create table st\_info(prn int, name varchar2(20),m1 number,m2 number,m3 number);

select \* from tab;

*#this will display no of tables present in database*

select \* from st\_info;

*#this will display content in the table*

desc st\_info;

 *#this will display the structure of table*

**2.**insert at least 10 rows in the table

insert into st\_info values (101,'Ria',8,9,4);

insert into st\_info values(2,'nandini',8,7,6);

insert into st\_info values(3,'aditi',4,6,9);

insert into st\_info values(4,'esha',8,9,8);

insert into st\_info values(5,'harsh',4,5,6);

insert into st\_info values(6,'rohit',3,7,4);

insert into st\_info values(7,'kashish',8,7,9);

insert into st\_info values(8,'niya',6,7,8);

insert into st\_info values(9,'ritika',8,7,9);

insert into st\_info values(10,'radhika,6,8,7);

**3.**add attribute total and perc to the table

alter table st\_info add total number;

alter table st\_info add perc number;

**4.**calculate total \& perc

update st\_info set total=m1+m2+m3;

update st\_info set perc=total/3;



