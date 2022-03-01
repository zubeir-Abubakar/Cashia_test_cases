# CASHIA TEST CASES



## Functionality

| Criteria                                        	| Applicable(y/n)  	|  Status 	|  Severity  	| Comments (if any)                                                                           	|
|-------------------------------------------------	|------------------	|---------	|------------	|---------------------------------------------------------------------------------------------	|
| Cashia app installation                         	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Cashia app uninstall                            	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Order placement                                 	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Wallet actions such as request, send and pay    	| No               	| Fail    	| High       	| App transactions in progress.                                                               	|
| App interaction/Navigation stability            	| Yes              	| Pass    	| low        	| App doesn't crash upon several navigation rather it slows down                                                  	|
| App location                                    	| Yes              	| Pass    	| Low        	| Setting location on won't affect the app                                                    	|
| App Alert                                       	| Yes              	| pass    	| low        	| App requests permission for location like  an alert and also disabling won't affect the app 	|
|  Search bar                                     	| Yes              	| pass    	| Medium        	| App gives results related to the search successfully tho it lucks autofocus as well as doesn't refresh from previous search history.                                       	|
| Edit profile and information                    	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Product to cart/purchase/Removal from cart      	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Placing a pickup order                          	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Placing a Delivery order                        	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Placing a Delivery order                        	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| Changing /update delivery location via Google + 	| Yes              	| Pass    	| Low        	| N/A                                                                                         	|
| UI/Stability of the app                         	| IN PROGRESS      	| N/A     	| N/A        	| N/A                                                                                         	|
| Notifications                                   	| NO               	| Fail    	| High       	| The app gives an error upon notification entrance                                           	|
| Validation                                	| Yes              	| pass    	| low        	| The amount validation both takes 2 decimal points as well as applies the mpesa limit. 	|
| App login                                 	| yes              	| pass    	| low        	| N/A                                            	|
| App logout                                	| yes              	| Fail    	| high        	| A user is redirected to the login page as well as token invalid message appears.        	|
| Adding a product to wish list                            	| yes              	| pass    	| low        	| N/A                                            	|
| Removing product from wish list (with the warning alert) 	| yes              	| pass    	| low        	| N/A                                            	|
| App products and products categories visible and interactive 	| yes              	| pass    	| low        	| N/A                                            	|

## Network Sharing and privacy.

| Criteria                                  	| Applicable(y/n)  	|  Status 	|  Severity  	| Comments (if any)                              	|
|-------------------------------------------	|------------------	|---------	|------------	|------------------------------------------------	|
| Link sharing and network sharing          	| Yes              	| Pass    	| Low        	| N/A                                            	|
| Internet Availability                     	| yes              	| Pass    	| Low        	| N/A                                            	|
| Internet not available/offline from start 	| Yes              	| Pass    	| medium        	| error processin your request message appears.                                            	|
| Offline in the middle of using app        	| yes              	| Fail    	| High       	| Displays the message Error processing request. 	|
| Pin for transactions                      	| Yes              	| Fail    	| High       	| Displays the message Error processing request. 	|
| Pin change                                	| yes              	| pass    	| low        	| N/A                                            	|
| Q.R code                                  	| yes              	| pass    	| medium     	| The code results returns message “not found”.  	|
| Privacy & security                        	| yes              	| Fail    	| High       	| The page doesn't fetch when allowing phone book access and takes the user to setting, and when allowed from there doesn't refresh from the app to apply the changes. 	|
