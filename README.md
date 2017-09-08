"# dbpractice"  
CREATE TABLE tbl_Products(serialNumber VARCHAR(10), name VARCHAR(50), description VARCHAR(250), price INT(11));  
select * from tbl_Products;


18.220.231.8  
root  
M@pirisoft062012   

select * from tbl_Products;  
alter table tbl_Products add primary key(serialNumber);  
insert into tbl_Products values ('A01', 'FitBit2', 'another tracker', 175);
