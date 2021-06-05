
# API Response Codes
Response code for API

|Code|Info| Description|
|--|--|--| 
|2XX|Success| It means the action was successfully received, understood, and accepted.|  
|3XX|Redirection| It means further action must be taken in order to complete the request.|
|4XX|Client Error| It means the request contains incorrect syntax or cannot be fulfilled.|
|5XX|Server Error| It means the server failed to fulfill an apparently valid request.  |

- ### E400
	_Bad Request_
  
  You have requested the page with some malformed or invalid parameters.
  
- ### E401
	_Unauthorized_
  
  Authorization token is not authorized, check extended error message in body for more details.

- ### E403
	_Forbidden_
  
  Access to the page/ resource has been restricted by the admin.

- ### E404
	_Resource or the page is not availble_
  
  This means that the url or the page you are trying to visit is not available on the  	server or it may removed from the server.

- ### E405
	_Method not allowed_
  
  You are accessing the page with wrong method. You have to check the guidelines for the API.
  
- ### E409
	_Conflict_
  
  TODO: add description

- ### E410
	_Gone_
  
  The session has expired
  
- ### E410
	_Length Required_

  Content-Length header was required, but not provided.

- ### E412
	_Precondition Failed_

  Content-Length header was required, but not provided.

- ### E413
	_Request Entity Too Large_

  Request Entity too Large
  
 - ### E429
	_Too Many Requests_

  Request rate limit exceeded, please try again later

- ### E500
	_Internal Service Error_

   Internal Service Error

- ### E500
	_Bad Gateway_

   Bad Gateway

- ### E503
	_Unavailable_

   Unavailable
