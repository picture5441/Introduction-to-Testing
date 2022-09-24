# Introduction-to-Testing

[Tiffany & Co.](https://www.tiffany.com/)
## Test case №1
Name: Adding an item to the bag

#### Preconditions

- Internet connection.
- Website https://www.tiffany.com/ is opened.

#### Test Steps

| ID                 | Test Step Description         | Expected Output                |   Actual Output                |
| ------------------ | ------------------------------------------------ | ----------------------------------------------------- |-----------|
| 1.                  | Mouse over _Jewerly_ category (in the Header)        | Pop-up menu _Jewerly_ is opened |  Pop-up menu _Jewerly_ is opened |   
| 2.                  | Select and click _Necklaces & Pendants (or any other)_ category (in the Pop-up menu)        | _Necklaces & Pendants (or any other)_ page is opened |       _Necklaces & Pendants (or any other)_ page is opened |  
| 3.1                  | Select and click on any picture of product (in the Body)        | _Product page_ is opened |   _Product page_ is opened | 
| 3.2                | Mouse over on any picture of product and click on the button "Add to Bag" (in the Body)        |Product is added to Bag |   Product is added to Bag |
| 4.1                  | Choose _Quantity_ of the product (optionally)        | _Quantity_ is chosen |   _Quantity_ is chosen |
| 5.1                  |Click the _Add to Bag_ button        | Pop-up menu _Add to Bag_ is opened. There is information about the product, total price and the button _Go to bag_ |   Pop-up menu _Add to Bag_ is opened. There is information about the product, quantity, the button _Remove_ and total price button _Estimate Total: xxx$ Checkout_ |
| 6                  | Click on the picture of _Bag_        | _Bag_ page is opened |   _Bag_ page is opened |

Point 4.1 may vary depending on the choice of product. It can be buttons _Quantity_, _Find your size_, _Chain Length_ and other.

#### Defects
- Point 4.1. Max Quantity of _Jewerly_ products is 5. 
- Point 5.1. Pop-up menu is not convenient for customers, because animation of loading of this menu is slow and customer should wait when pop-up menu is opening completely, otherwise it will close.

## Test case №2
Name: Finding a store in your city

#### Preconditions

- Internet connection.
- Website https://www.tiffany.com/ is opened.
- Allow/Not allow to show your location.

#### Test Steps

| ID                 | Test Step Description         | Expected Output                |   Actual Output                |
| ------------------ | ------------------------------------------------ | ----------------------------------------------------- |-----------|
| 1.                  | Click on the picture _Location_ (in the Header)        | _Location_ page is opened |  _Location_ page is opened | 
| 2.1                  | Click and select categories _Find stores within_, _All Services_ and input _city, state or zip_ (optionally)       | Information about store is showed |  Information about store is showed | 
| 2.2                  | Click on the button _View all stores_        | _All Stores_ page is opened |  _All Stores_ page is opened | 
| 3.1                  | Click on the button _Find a store_        | _Stores in your city_ page is opened |  _Map of your city_ is opened | 

#### Defects
- Point 2.1. If customer don`t input any information in the field _city, state or zip_, the information about stores will be "Sorry, no results matched your search". For example, to solve this problem field _city, state or zip_ must be requiring to input.
