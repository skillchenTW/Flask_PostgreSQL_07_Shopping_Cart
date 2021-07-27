CREATE TABLE product (
	pid serial PRIMARY KEY,
	code VARCHAR ( 100 ) NOT NULL,
	name VARCHAR ( 100 ) NOT NULL,
	image VARCHAR ( 100 ) NOT NULL,
	category VARCHAR ( 50 ) NOT NULL,
	price INT NOT NULL,
	discount INT NOT NULL
);


INSERT INTO
    product(code,name,image,category,price,discount)
VALUES
    ('00001','Samsung Galaxy A10S','2.jpg', 'Mobile', 520, 100),
    ('00002', 'Samsung Galaxy Win Duos', '3.jpg', 'Mobile', 1600, 500),
    ('00003', 'Women Summer Spaghetti Strap Down', '4.jpg', 'Woman Dresess', 2020, 1250);
	
	
select * from product;	