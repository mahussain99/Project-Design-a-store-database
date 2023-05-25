# Project-Design-a-store-database
Create your own store! Your store should sell one type of things, like clothing or bikes, whatever you want your store to specialize in. You should have a table for all the items in your store, and at least 5 columns for the kind of data you think you'd need to store. You should sell at least 15 items, and use select statements to order your items by price and show at least one statistic about the items.

Create Table MAH (Id Integer Primary Key, Locations Text,  Asile Integer, Item_Name Text, Price Integer, Quantity Integer);

INSERT INTO MAH VALUES ( 1, "Paterson", 2, "Bike", 250, 1);
INSERT INTO MAH VALUES ( 2, "Clifton", 3, "Computer", 1050, 2);
INSERT INTO MAH VALUES ( 3, "Wayne", 5, "Furniture", 3500, 4 );
INSERT INTO MAH VALUES ( 4, "Totowa", 6, "Tiles", 12, 8 );
INSERT INTO MAH VALUES ( 5, "Bloomfiled", 1, "Snow_Blower", 350, 1 );
INSERT INTO MAH VALUES ( 6, "FairLown", 8, "Vegetable", 450, 100 );
INSERT INTO MAH VALUES ( 7, "Bloomfiled", 1, "Snow_Blower", 550, 2 );
INSERT INTO MAH VALUES ( 8, "Bloomfiled", 1, "Drill_Mech", 1350, 10 );

Select *
From Mah;

Select Item_Name, Price
From Mah
Order by Price Asc;

Select Avg(Price) as AVG_Price
From Mah;

Select sum(Price) as sum_Price
From Mah;

Select Max(Price) as Max_Price
From Mah;

