##Each readme should have the following five elements:
* Integration Logo/Link
* Name of Integration with Brief Description and How the Astronomer Integration works
* Methods Section
* Configuration Section (with Screenshots of Parameters where Available)
* Sample Response

![alt text](/img/logo.png "Aries Integration for [INSERT INTEGRATION NAME HERE]")

#Aries Integration for [INSERT INTEGRATION NAME HERE]

This is an integration for [INTEGRATION NAME]([LINK TO INTEGRATION WEBSITE]), [BRIEF DESCRIPTION OF INTEGRATION]. The Aries Integration makes an asynchronous API call on the schedule specified.

##Methods
This integration uses [NUMBER OF METHODS] method. [IF ONLY ONE METHOD, SPECIFY THAT IT IS CALLED BY DEFAULT]

###1) [Method One NAME]
`methodOneName` - Returns data about [XYZ].

###2) [Method Two Name]
`methodTwoName` - Returns data about [XYZ].

###3) [Method Three Name]
`methodTwoName` - Returns data about [XYZ].

##Configuration
This integration takes in [NUMBER OF REQUIRED PARAMETERS] required parameters and [NUMBER OF OPTIONAL PARAMETERS] optional parameters that can be used to modify the data being requested.

###Consumer Key
[INSERT BRIEF DESCRIPTION OF PARAMETER AND WHERE IT CAN BE FOUND. INCLUDE SCREENSHOT IF APPLICABLE]
EXAMPLE:
The consumer key is assigned under the Admin Panel. The consumer key is located in the Admin Panel under Settings > API > Keys/Apps. Once the user is created, it will display the consumer key and secret and WILL NOT be able to be seen again so make sure to store it somewhere safe.
```javascript
"consumerKey": "ck_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
```

###Consumer Secret - OPTIONAL
EXAMPLE: The consumer key is assigned under the Admin Panel. The consumer key is located in the Admin Panel under Settings > API > Keys/Apps. Once the user is created, it will display the consumer key and secret and WILL NOT be able to be seen again so make sure to store it somewhere safe.
```javascript
"consumerSecret": "cs_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
```

##Response
This is an example response when a query is made using the "customers/2" endpoint.
```javascript
{
  "customer": {
    "id": 2,
    "created_at": "2015-01-05T18:34:19Z",
    "email": "john.doe@example.com",
    "first_name": "James",
    "last_name": "Doe",
    "username": "john.doe",
    "last_order_id": null,
    "last_order_date": null,
    "orders_count": 0,
    "total_spent": "0.00",
    "avatar_url": "https://secure.gravatar.com/avatar/ad516503a11cd5ca435acc9bb6523536?s=96",
    "billing_address": {
      "first_name": "John",
      "last_name": "Doe",
      "company": "",
      "address_1": "969 Market",
      "address_2": "",
      "city": "San Francisco",
      "state": "CA",
      "postcode": "94103",
      "country": "US",
      "email": "john.doe@example.com",
      "phone": "(555) 555-5555"
    },
    "shipping_address": {
      "first_name": "John",
      "last_name": "Doe",
      "company": "",
      "address_1": "969 Market",
      "address_2": "",
      "city": "San Francisco",
      "state": "CA",
      "postcode": "94103",
      "country": "US"
    }
  }
}
```

### Astronomer Formatted Response
[INCLUDE IF DIFFERENT FROM THE RAW RESPONSE - ex. [Fixer.io](https://github.com/aries-data/aries-activity-fixer-source)]

### Roadmap
There are additional endpoints available here: LINK TO DOCS OF INTEGRATION. If you are interested in having the intgration extended, please email support@astronomer.io