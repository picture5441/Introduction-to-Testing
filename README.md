# Introduction-to-Testing

[Tiffany & Co.](https://www.tiffany.com/)
## Test case №1
Name: Adding an item to the bag

#### Preconditions

- Internet connection.
- Product page is opened.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Select and click on any picture of product  | _Product page_ is opened | _Product page_ is opened |
| 2.  | Choose _Quantity_ of the product | _Quantity_ is chosen     | _Quantity_ is chosen     |
| 3.    |    Click the _Add to Bag_ button                                         |     	Pop-up menu _Add to Bag_ is opened. There is information about the product, total price and the button Go to bag                     |        Pop-up menu _Add to Bag_ is opened. There is information about the product, quantity, the button Remove and total price button _Estimate Total: xxx$ Checkout_                  |

## Test case №2
Name: Finding a store in your city

#### Preconditions

- Internet connection.
- Website https://www.tiffany.com/ is opened.
- Allow/Not allow to show your location.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Click on the picture _Location_  | _Location_ page is opened | _Location_ page is opened |
| 2.  | Click and select categories _Find stores within_, _All Services_ and input _city, state or zip_ | Information about store is showed     | Information about store is showed     |
| 3.    |     Click on the button _Find a store_          |     	_Stores in your city_ page is opened         |        _Map of your city_ is opened    |

## Test case №3
Name: Viewing _Main_ page  

#### Preconditions

- Internet connection.


#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Open the site and close all popups in the way that content is clickable | Header top lings, logo image, header navigation bar, search, shopping bag, video, Shop by Category, popular products, Stories, The Tiffany Experience, footer navigation, footer copyright blocks are rendered |Header top lings, logo image, header navigation bar, search, shopping bag, video, Shop by Category, popular products, Stories, The Tiffany Experience, footer navigation, footer copyright blocks are rendered|


## Test case №4
Name: Product search

#### Preconditions

- Internet connection.
- Main page is opened.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Click on the picture _Search_, click on the search input and type askdkskdaaksdkakdk text | _No product found page_ is opened | _No product found page_ is opened and text _Sorry, no results matched your search for"askdkskdaaksdkakdk"_ is rendered |
| 2.  | Click on the picture _Search_, click on the search input and type _Jewerly_ text| Product page is opened    | Product page is opened and text _No results found for"Jewerly".We found 2907 results for"Jewelry"._ is displayed. _Category_, _Designers & Collections_, _Material_, _Gemstones_, _Price_ is rendered|


## Test case №5
Name: Viewing _Men’s Watches_ page  

#### Preconditions

- Internet connection.
- Website https://www.tiffany.com/ is opened.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Click on the _Fine Watchs_ title in the header | Pop-up menu is opened |Pop-up menu is opened |
| 2.  | Click on the _Men’s Watches_ title in a pop-up menu | _Men’s Watches_ page is opened | _Men’s Watches_ page is opened. Also _Men’s Watches_ page contains _header, footer, Filter by, Sort by, Products_ blocks  |


## Test case №6
Name: Product Sort

#### Preconditions

- Internet connection.
- Sort is not selected.

#### Test Steps

| ID  | Test Step Description            | Expected Output                                                                                                    | Actual Output                                                                                           |                                                                   |
| --- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| 1.  | Open _Men’s Watches_ page        | _Men’s Watches_ page is opened                                                                                     | _Men’s Watches_ page is opened                                                                          |                                                                   |
| 2.  | Click on pop-up _Sort by_ button | List of _Sort menu_ is opened                                                                                      | List with options _(Recommendations, New to Tiffany, Price: High to Low, Price: Low to High)_ is opened |                                                                   |
| 3.  | Click on the _Recommendations_ | All products are displayed from  recommendations from other users, selected option appears at the sorts block                                       | All products are displayed from  recommendations from other users, selected option appears at the sorts block |
| 4.  | Click on the _New to Tiffany_ | All new products are displayed, selected option appears at the sorts block | All new products are displayed, selected option appears at the sorts block  |
| 5.  | Click on the _Price: High to Low_ | All products are displayed from the most expensive to the cheapest one, selected option appears at the sorts block | All products are displayed from the most expensive to the cheapest one, selected option appears at the sorts block |
| 6.  | Click on the _Price: Low to Hgh_ | All products are displayed from the cheapest to the most expensive one, selected option appears at the sorts block | All products are displayed from the cheapest to the most expensive one, selected option appears at the sorts block |


## Test case №7
Name: Viewing the _Empty bag_ 

#### Preconditions

- Internet connection.
- Nothing is added to the bag.


#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Open the site and close all popups in the way that cart in the header is clickable|  _Main page_ is opened| _Main page_ is opened|
| 2.  | 	Click on the bag in the header |  _Shopping bag_ page is opened|_Shopping bag_ page is opened. _Your shopping bag is empty_ text is displayed|

## Test case №8
Name: Contacting a Client Advisor 

#### Preconditions

- Internet connection.
- _Product page_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Contacting a Client Advisor_ button |  Pop-up _Contacting a Client Advisor_ menu is opened| Pop-up _Contacting a Client Advisor_ menu is opened|
| 2.  | 	Click on the _Chat online_ button |  Chatting menu is opened | Chatting menu is opened with messages _Welcome to Tiffany & Co._, _Click below to chat with our automated Virtual Assistant_, _Virtual Assistant is a chatbot application, provided and powered by Quiq, our third-party service provider. We and our service provider will record and maintain a transcript of this chat. For more information about our privacy practices, please see our Privacy Notice. By clicking “Start Chatting,” you acknowledge the above._ |
| 4.  | 	Click on the _Start chatting_ button |  Chat is started | Chat is started with message _How can we assist you today_ and list of choices _(Find a product, Help with my order, Chat with a Client Advisor, Product Care & Repair)_  |


## Test case №9
Name: Find a product in _Contacting a Client Advisor_ 

#### Preconditions

- Internet connection.
- Pop-up menu _Contacting a Client Advisor_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Find a product_ button |  Messages with help are displayed. |Messages with help are displayed. _One moment please. A Client Advisor will be with you shortly. Kym has joined the chat. Welcome to Tiffany & Co. My name is Kym, how may I help you today?_|
| 2.  | 	Message _ddpspfsdpfpsdpfpdsf_ is sent |  Chat is stopped | Another message _Welcome to Tiffany & Co. My name is Kym, how may I help you today? Thank you for contacting Tiffany & Co. If you have any further questions, we can be contacted at 1-800-843-3269. Our hours of operation are as follows: Monday to Friday: 8:00 am to 10:00 pm (12 am midnight on Live Chat) Saturday: 9:00 am to 9:00 pm Sunday: 10:00 am to 9:00 pm EST. How satisfied were you with the service you received from your Tiffany & Co. Client Advisor during this chat?_  |

## Test case №10
Name: Help with my order in _Contacting a Client Advisor_ 

#### Preconditions

- Internet connection.
- Pop-up menu _Contacting a Client Advisor_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Help with my product_ button |  Messages with help are displayed |Messages with help are displayed. _Sure, are you looking to:_ List of buttons _(Place an order, Track my order, Return or Exchange, Request help)_ is opened |


## Test case №11
Name: Help with my order in _Contacting a Client Advisor_ 

#### Preconditions

- Internet connection.
- Pop-up menu _Contacting a Client Advisor_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Help with my product_ button |  Messages with help are displayed |Messages with help are displayed. _Sure, are you looking to:_ List of buttons _(Place an order, Track my order, Return or Exchange, Request help)_ is opened |

## Test case №12
Name: Chat with a Client Advisor in _Contacting a Client Advisor_ 

#### Preconditions

- Internet connection.
- Pop-up menu _Contacting a Client Advisor_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Contacting a Client Advisor_ button |  Messages with help are displayed |Messages with help are displayed. _One moment please. A Client Advisor will be with you shortly. Kym has joined the chat. Welcome to Tiffany & Co. My name is Kym, how may I help you today?_|
| 2.  | 	Message _ddpspfsdpfpsdpfpdsf_ is sent |  Chat is stopped | Another message _Welcome to Tiffany & Co. My name is Kym, how may I help you today? Thank you for contacting Tiffany & Co. If you have any further questions, we can be contacted at 1-800-843-3269. Our hours of operation are as follows: Monday to Friday: 8:00 am to 10:00 pm (12 am midnight on Live Chat) Saturday: 9:00 am to 9:00 pm Sunday: 10:00 am to 9:00 pm EST. How satisfied were you with the service you received from your Tiffany & Co. Client Advisor during this chat?_  |

## Test case №13
Name: Product Care & Repair in _Contacting a Client Advisor_ 

#### Preconditions

- Internet connection.
- Pop-up menu _Contacting a Client Advisor_ is opened.



#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | 	Click on the _Product Care & Repair_ button |  Messages with help are displayed |Messages with help are displayed. _Preserve the beauty of your Tiffany jewelry and accessories with cleaning, care and repair._ List of buttons _(Request a repair, Product care)_ is opened|
| 2.  | 	Click on the _Request a repair_ button |  Messages with help are displayed | Messages _We are delighted to offer cleaning and repair for most Tiffany products. You may either bring your item to the Tiffany store nearest you or send in your item via mail. If you choose to send your item via mail, please fill out the Service Request Form._ are displayed. Buttons _Service Request Form, More information, Okay thanks_ are displayed  |
| 3.  | 	Click on the _Okey thanks_ button |  Messages with help are displayed | Message _Did you find the answer to your question?_ is displayed. Emoji _Cool, Uncool_ are availible. |

