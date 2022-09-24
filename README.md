# Introduction-to-Testing

[Tiffany & Co.](https://www.tiffany.com/)
## Test case №1
Name: Adding an item to the bag

#### Preconditions

- Website https://www.tiffany.com/ is opened.

#### Test Steps

| ID                 | Test Step Description         | Expected Output                |   Actual Output                |
| ------------------ | ------------------------------------------------ | ----------------------------------------------------- |-----------|
| 1.                  | Mouse over _Jewerly_ category (in the Header)        | Pop-up menu _Jewerly_ is opened |  Pop-up menu _Jewerly_ is opened |   
| 2.                  | Select and click _Necklaces & Pendants (or any other)_ category (in the Pop-up menu)        | _Necklaces & Pendants (or any other)_ page is opened |       _Necklaces & Pendants (or any other)_ page is opened |  
| 3.1.                  | Select and click on any picture of product (in the Body)        | _Product page_ is opened |   _Product page_ is opened | 
| 3.2.                | Mouse over on any picture of product and click on the button "Add to Bag" (in the Body)        |Product is added to Bag |   Product is added to Bag |
| 4.1.                  | Choose _Quantity_ of the product (optionally)        | _Quantity_ is chosen |   _Quantity_ is chosen |
| 5.1.                  |Click the _Add to Bag_ button        | Pop-up menu _Add to Bag_ is opened. There is information about the product, total price and the button _Go to bag_ |   Pop-up menu _Add to Bag_ is opened. There is information about the product, quantity, the button _Remove_ and total price button _Estimate Total: xxx$ Checkout_ |
| 6                  | Click on the picture of _Bag_        | _Bag_ page is opened |   _Bag_ page is opened |

Point 4.1 may vary depending on the choice of product. It can be buttons _Quantity_, _Find your size_, _Chain Length_ and other.

#### Defects
- Point 4.1. Max Quantity of _Jewerly_ products is 5. 
- Point 5.1. Pop-up menu is not convenient for customers, because animation of loading of this menu is slow and customer should wait when pop-up menu is opening completely, otherwise it will close.
