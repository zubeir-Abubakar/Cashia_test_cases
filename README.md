Project name 	Cashia App									
Module Name	Android Version 1.6.1									
Created by	Abubakar Towfiq									
Creation Date	07/02/2022									
Reviewed by										
Review day	MM/DD/YYYY									
										
										
										
				FUNCTIONALITY TEST						
										
Test scenario ID	Test Scenario Description	Test Case ID	Test Case Description	Test Data	Post Conditions	Expected results	Actual results	 Status	Severity	Comments (if any)
TST_CASHIA_001	The App installation	TC_Cashia_installation_001	" install the app through 
gmail or app tester."	"Username:qwerty@
cashia.com
Password:xxxxxxxx"	User should be able to have a gmail with the permission to test and download the app	Get started and login page	Get started login page.	Pass	Low	N/A
										
TST_CASHIA_003	The app login	TC_Cashia_login_002	"1- Login using Gmail account
 
2-Login  using apple ID"	"Gmail Account: accounts :qwerty@
gmail.com

Gmail Account: accounts :qwerty@
icloud.com"	"1- A valid Gmail account that has acces to your android
device .

2-A valid Icloud account that has acces to your ios
 device ."	"1- Home page.

2- Home page."	"1- Get started page then  Home page.
2- Get started page then  Home page"	Pass	Low	N/A
										
TST_CASHIA_003	Home page	TC_Cashia_Homepage_003	"Tap on the get started to be
 taken to the home page"	Cashia homepage	N/A	"Images are visible and 
do not occupy much space and cropped"	"Images are visible and do not 
occupy much space and cropped"	Pass	low	N/A
										
TST_CASHIA_004	Location	TC_Cashia_Location_004	"Tap on the top navbar in home
page to edit your location"	"N/A

2- kariobangi stage"	"1- Tap on allow button on 
the pop up to have access
 to your location.

2-N/A"	"1- The pin will move to your 
current location and display the coordinates.

2- The pin will move to the stated location."	"1- The pin will move to your 
current location and display the coordinates.

2- The pin will move to the stated location."	Pass	Low	"Setting the location on/Off
 from the settings section 
doesn't affect the stability of the app"
										
TST_CASHIA_005	Pages Navgation icons	TC_Cashia_Navigation_005	"Tap on the different navigation
 pages down the page"	"1-Merchant logo tap
2- Apples
3- Apples.
4-User"	"1- N/A
2-N/A
3-Must be logged on.
4-Must be logged in."	"1- Pictures/logo of merchants.
2- Display of both merchant an products of the same name as the searched one.
3- The orders in progress If there is any.
4- Display with the profile picture as well as 'Go to wallet button'"	"1- Pictures/logo of merchants.
2- Display of both merchant an products of the same name as the searched one.
3- The orders in progress If there is any.
4- Display with the profile picture as well as 'Go to wallet button'"	Pass	Low	N/A
										
TST_CASHIA_006	Search_bar	TC_Cashia_search bar_006	Navigate to the search icon	Cashia app search 	"Must navigate to the search 
icon on the bottom navbar"	"To display the searched information
 and save data as search history."	"Displays the searched character as 
well as saves the history results.

-Text history seems
 cropped
-The searched merchant doesn't enter into history and thus only products do.
-Lacks autofocus.
-Doesn't refresh once used and closed."	Fail	High	To be worked on
										
TST_CASHIA_007	Order placement	TC_Cashia_placement_007	"Tap on any merchnat products
 to purchase."	Cashia app homepage	"1- Place order and accept
transactions.
2- Change the delivery to pickup"	"1- A receipt of the product 
purchased as wel as delivery details.

2- Receipt as well as pickup station"	"1- A receipt of the product 
purchased as well as delivery details.

2- Receipt as well as pickup station"	Pass	Medium	N/A
										
TST_CASHIA_008	Order removal from cart	TC_Cashia_OrderRemoval_008	Add any product to cart	Red valvet merchant	Swipe to delete	"Swiping gives an option 
to delete."	"Swiping gives an option 
to delete."		Low	
										
										
TST_CASHIA_009	order delivery details change	TC_Cashia_orderDelivery_009	"On the delivery page change
 the location or the delivery to happen."	User data	N/A	"The new location data will be 
taken in and thus be used as the delivery location details."	"The new location data will be 
taken in and thus be used as the delivery location details."	Pass	Low	 N/A
										
TST_CASHIA_010	Transactions	TC_Cashia_Transactions_010	"Navigate to profile and tap on
 go to wallet"	N/A	N/A	N/A	N/A	INPROGRESS	High	"WORKING ON THE NEW 
DESIGNS FOR TRANSACTIONS."
										
TST_CASHIA_011	Unistalling app	TC_Cashia_unistalling app_011	"Drag and drop to thrash or 
uninstall manually"	Cashia app mobile	"Tap and hold to get options
 and deletee the app."	"The app deletes all cache and 
data as well as unistall successfully"	"A succesful message appears to
 indicate the app is succesfully uninstalled."	Pass	Low	N/A
										
TST_CASHIA_0012	Notification section	TC_Cashia_notication_012	Notification setion icon 	Product purchase	"Tap to add a product to 
your cart and checkout 
and have a succesful 
transaction"	"A display of all the transactions
 wheather pending , succesful or failed.
A display of all the message of prouducts purchased as well as arrived products"	"And error pop's up saying ' there 
was an error processing your request'."	Fail	High	N/A
										
TST_CASHIA_013	UI && Usability of the app	TC_Cashia_UI&Usability_013	The app testing UI and usability	Cashia mobile app	"App functionality and 
interaction"	"User interaction and app 
stability fine."	"The app doesn't crash when a user
 is using and is smooth as well as the content is well spaced and arraged."	Pass	Low	"The app usability and
 UI is still under progress."
										
										
				Network and sharing.						
										
	Test scenario ID	Test scenario Description	Test Case ID	Test Case Description.	Expected results	Actual Results	Status	Severity	Comments (If any)	
	TST_CASHIA_013	"Link sharing and network 
sharing"	TC_Cashia_link/network_sharing	"Tap on any product and 
on top navbar you will see share tap on it and copy the link."	"The link will be succesfully 
coppied with a message."	"The link is succesfully copied
 with a message to indicate it is coppied and can be shared."	Pass	Low	N/A	
										
										
				Privacy						
										
Test scenario	Test scenario Description 	Test case ID	Test Case Description	pre condition	Test data	Expected Results	Actual Results	Status	Severity	Comments (if any)
TST_CASHIA_OO14	Wallet pin Change	TC_Cashia_Wallet_change_pin	Ente a valid phone number	"


Valid number"	25470000000	A verificaion code is sent to the number and a new pin input in box field provides.	A box input for the verification code sent to the number is sent to verify your change request and new pin box input is asked for.	Pass	LOW	N/A
										
TST_CASHIA_0015	Pin for transactions	TC_Cashia_pin_transactions	Must checkout for cart	enough amount of money in wallet	"1- Wrong pin
2- Correct pin"	"1- An error message stating 'inccorect pin'.
2- Succesful transaction message."	"1- Error processing request.
2- Pending message ."	Fail	High	The new designs is work in progress.
										
										
										
										
										