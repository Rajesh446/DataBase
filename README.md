create table product
(
id varchar2(20) primary key,
name varchar2(20) not null,
price varchar2(50)
)


--------------------------------------------------------------------------------------------------------------------------------------
insert into product values('P-101','s-7','55,000')
--------------------------------------------------------------------------------------------------------------------------------------

create table category
(
id varchar2(20) primary key,
name varchar2(20) not null,
discreption varchar2(50)
)

--------------------------------------------------------------------------------------------------------------------------------------
insert into category values('c-101','mobile','samsung')

--------------------------------------------------------------------------------------------------------------------------------------

create table supplier
(
id varchar2(20) primary key,
name varchar2(20) not null,
address varchar2(50)
)

--------------------------------------------------------------------------------------------------------------------------------------
insert into product values('s-101','Bigc','Hyderabad')
--------------------------------------------------------------------------------------------------------------------------------------
