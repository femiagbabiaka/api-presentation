# How do you API even?

#HSLIDE
Goals: *learn the basics of using our API and RESTful API's.*
Non Goals: *learn Postman in-depth.*

#HSLIDE
API stands for Application Program Interface. But to understand what an API is, you must first understand what a URL is. -- Ancient Femi Proverb

#HSLIDE
URL: Uniform Resource Locator.

http://www.activecampaign.com/

http://www.activecampaign.com/enterprise/

https://testfemi123.activehosted.com/api/3/contacts/

#HSLIDE
A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.

*API v3 is RESTful.*
*API v1 (https://activecampaign.com/api/example/index.php) is not.*

#HSLIDE

Wait.. what do GET, PUT, POST, and DELETE mean?

#HSLIDE

`contact_sync` example:

Request:
```
HTTP POST
https://testfemi123.api-us1.com/admin/api.php?action=contact_sync
api_action=contact_sync&api_key=API_KEY&api_output=json&email=femi@activecampaign.com
```
Response:
To POSTMAN!


Request:
`api v3 contactList` example:
```
HTTP GET
https://testfemi123.activehosted.com/api/3/contacts/
```

Response:
To POSTMAN!

#HSLIDE

Questions?
Use cases?
