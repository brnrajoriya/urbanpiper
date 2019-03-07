Introduction



Authentication
Token authentication
For accessing the endpoints, a combination of username and API key is required. You can requesting for them here[mailto:support@urbanpiper.com?subject=Need%20API%20access].

The API credentials should be passed in using the Authorization header value like so:

Authorization: apikey <USERNAME>:<API KEY>

You must replace USERNAME and API KEY with the ones issued to you.



Configuration
These endpoints should be used to configure the UrbanPiper platform with all the necessary data required to setup the merchant’s online Order Management System (OMS). As of now, the platform allows the following configurations to be managed through APIs:

Stores
Categories
Items/Products
Item Option Groups
Item Options