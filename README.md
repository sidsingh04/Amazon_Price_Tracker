# Amazon_Price_Tracker
This is a flask project that helps user to keep the history of prices of the products availaible on amazon site<br /><br />

WORKING IDEA ::<br/> This app extracts date from the amazon url given from the user and extracts price and other relevant information about the product using web scrapping by beautiful soup in python.<br /><br /><br />

Procedure to use::<br /> The landing page of the site contains all the relevant procedure to use the app effectively and in correct manner<br /><br /><br />

Important Points::<br />
1.When the first time the program is loaded on the computer then you need to migrate the sqlite database in order to 
  set-it-up.<br /><br />
2.The app will allow the user to track the price of that product only ones a day.<br /><br />
3.This app will show only 7 slots of price history per product.If the all the 7 slots are full and you add a new 
  tracker then it would rewrite on the oldest tracker present in the history.<br /><br />
4.If the app shows the error that no data is fetched from the url,then delete that product and add a new product with correct url.The system wouldnot automatically remove the trash trackers.<br /><br /> 
