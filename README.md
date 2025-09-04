# PROG6112_Assessment1_ST10445866

Online Links:
GitHub Repository Link:
https://github.com/SekwenaBotshelo/PROG6112_Assessment1_ST10445866.git 
 
PLEASE NOTE THAT I COULD NOT ACCESS THE GITHUB REPOSITORY THAT YOU PROVIDED.
SO I HAVE CREATED A GITHUB REPOSITORY WHERE YOU CAN ACCESS THE PROJECT FILES FOR YOUR OWN VIEWING.

YouTube Unlisted Video Link:
https://youtu.be/la3VMAuGrKc 
 
Project Description:
Section A: Series Management Java Project
Description:
This is a Java application that is used to manage a list of television shows. Users can verify age limitations while searching, updating, and deleting series records. The system uses ArrayList<SeriesModel> to store series’ in memory.

Class Summaries:
•	Series
  o	This class represents a comprehensive TV show that includes the title, rating, age limit,  genre, and year of release.
•	SeriesModel
  o	A series' ID, name, age restriction, and episode count are displayed simply (used for storing in the program).
•	Prog6112PracticalAssignment
  o	Console menus, CRUD operations, and SeriesModel object management are handled by the main application class.
  
Function Description:
•	Capture New Series
o	Provides ID, name, age restriction (verified between 2 and 18), and episode prompts.
  o	Creates an ArrayList<SeriesModel> to hold the new series.
•	Search for a Series
  o	Searching by Series ID or Series Name is possible.
  o	If a series is discovered, series information are displayed.
•	Revise the Age Limitation
  o	Identifies a series.
  o	Verifies newly entered ages (2–18).
  o	The series record is updated.
•	Delete a Series
  o	This action eliminates a series from the list based on its ID.
•	Print Report
  o	Produces a structured report that includes all of the stored series.
  o	If there are no series, a notice is displayed.
•	Validation
  o	The age range must be between 2 and 18.
  o	Invalid entries are prevented using numerical validation.

Unit Test Summaries:
Test Method	Purpose	Expected Outcome
TestSearchSeries()	Look up current series by ID.	Returns matching SeriesModel
TestSearchSeries_SeriesNotFound()	Look up non-existent series	Returns null
TestUpdateSeries()	Update the age limit for a legitimate series ID.	Returns true and updates value
TestDeleteSeries()	Remove current series by ID.	Returns true and removes series
TestDeleteSeries_SeriesNotFound()	Try to remove any non-existent series.	Returns false
TestSeriesAgeRestriction_AgeValid()	Verify the age restriction (between 2 and 18).	Returns true
TestSeriesAgeRestriction_AgeInValid()	Verify the age restriction outside of the range.	Returns false
(Farrel, 2023)
 
Section A: Retail inventory Java Project
Description:
This is a Java console application called RetailInventoryAppST10445866 that is used to manage a store's inventory of groceries and electronics. Products can be added, sold, inventory reports can be generated, and transactions can be tracked.

Class Summaries:
•	Product
  o	Base class for generic goods
•	Electronics
  o	Product subclass with a months-long warranty
•	Grocery
  o	Product subclass with an expiration date
•	Inventory
  o	Oversees a number of sales, transactions, and items.
•	InputHelper
  o	Manages user input (string, date, double, and integer).
•	RetailInventoryAppST10445866
  o	The console interface is provided by the main class.
•	InventoryTests
  o	Unit tests for methods in the Inventory class
•	ProductTests
  o	Unit tests for the classes of groceries, electronics, and products
Function Description:
•	Add Products: 
  o	Ensures that the inventory is complete by adding groceries or electronics.
•	Sell Products: 
  o	Keeps track of transactions, advises when stock is low or unavailable, and updates stock.
•	Reports: 
  o	Produces transaction and inventory reports that include stock alerts.
•	Search: 
  o	Look up products by name and get information related to a given category.

Unit Test Summary – InventoryTests
Test Method	Purpose	Expected Outcome
testAddProduct	Add product to inventory	Product added successfully
testAddProductInventoryFull	Attempt to add product beyond inventory capacity	Product not added (null returned)
testSellProduct	Sell available stock	Stock decreases accordingly
testGetProductByName	Retrieve product by name	Returns correct product or null
testTransactionHistory	Check stock and transaction after sales	Stock updated and transactions recorded

Unit Test Summary – ProductTests
Test Method	Purpose	Expected Outcome
testproductGetter	Verify Product getters	Correct values returned
testProductSell	Sell Product	Stock decreases or remains if insufficient
testElectronicsWarranty	Verify Electronics Warranty	Correct Warranty returned
testElectronicsReport	Verify Electronics report string	Report contains product info
testGroceryExpiryDate	Verify Grocery expiry date	Correct date returned
testGroceryReport	Verify Grocery report string	Report contains product info

(Farrel, 2023) (Krysik, 2024) (ADMIN, 2025) (ChatGPT, 2025)

Referances:
Farrel, J. (2023). Java Programming. Boston: Cengage.
Krysik, A. (2024, December 9). How to Build an Inventory Management System: Key Steps and Tips. Retrieved from STRATO FLOW: https://stratoflow.com/how-to-build-inventory-management-system/
ADMIN. (2025, August 30). How to Create Inventory Management System in Java NetBeans. Retrieved from Inventory System Solutions: https://inventorysystemsolutions.com/how-to-create-inventory-management-system-in-java-netbeans/
ChatGPT. (2025). ChatGPT. Retrieved from ChatGPT: https://chatgpt.com
