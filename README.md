# hibernate-tables
  Tables creation in DataBase for example for user,category,supplier,product
    
    USER
    _____________________
    create table user
    (
    name varchar2(20) primary key,
    id varchar2(20) not null,
    password varchar2(20) not null,
    mobile varchar2(20) not null,
    mail_id varchar(20) not null,
    )
    
    CATEGORY
    _____________________
      create table category
    (
    id varchar2(20) primary key,
    name varchar2(20) not null,
    descrption varchar2(100)
    )
    
    SUPPLIER
    ________________________
     create table supplier
    (
    id varchar2(20) primary key,
    name varchar2(20) not null,
    address varchar2(50)
    )
    
    PRODUCT
    ________________
     create table supplier
    (
    id varchar2(20) primary key,
    name varchar2(20) not null,
    price number
    )
  _________________________________________________________
    
    To insert into these tables for example
     
    INSERT INTO USER (NAME,ID,PASSWORD,MOBILE,MAIL_ID)
    
    INSERT INTO CATEGORY (ID,NAME,DESCRIPTION)
    
    INSERT INTO SUPPLIER (ID,NAME,ADDRESS)
    
    INSERT INTO PRODUCT (ID,NAME,PRICE)
    
    ___________________________________________________________________
    
     To update into these tables for example
    
     UPDATE SUPPLIER
      SET ID = 45
      WHERE NAME = 'MOBILE'
    
    
    
