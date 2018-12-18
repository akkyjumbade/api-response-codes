
# API Response Codes
Response code for API

|1XX|Informational| It means the request has been received and the process is continuing.|  
|--|--|
|2XX|Success| It means the action was successfully received, understood, and accepted.|
|--|--|
|3XX|Redirection| It means further action must be taken in order to complete the request.|  
|--|--|
|4XX|Client Error| It means the request contains incorrect syntax or cannot be fulfilled.|
|--|--|
|5XX|Server Error| It means the server failed to fulfill an apparently valid request.|

- ### ERRR-400
	_Bad Request_
  
  You have requested the page with some malformed or invalid parameters.
  
- ### ERRR-401
	_Unauthorized_
  
  Authorization token is not authorized, check extended error message in body for more details.

- ### ERRR-403
	_Forbidden_
  
  Access to the page/ resource has been restricted by the admin.

- ### ERRR-404
	_Resource or the page is not availble_
  
  This means that the url or the page you are trying to visit is not available on the  	server or it may removed from the server.

- ### ERRR-405
	_Method not allowed_
  
  You are accessing the page with wrong method. You have to check the guidelines for the API.
  
- ### ERRR-409
	_Conflict_
  
  TODO: add description

- ### ERRR-410
	_Gone_
  
  The session has expired
  
- ### ERRR-410
	_Length Required_

  Content-Length header was required, but not provided.

- ### ERRR-412
	_Precondition Failed_

  Content-Length header was required, but not provided.

- ### ERRR-413
	_Request Entity Too Large_

  Request Entity too Large
  
 - ### ERRR-429
	_Too Many Requests_

  Request rate limit exceeded, please try again later

- ### ERRR-500
	_Internal Service Error_

   Internal Service Error

- ### ERRR-500
	_Bad Gateway_

   Bad Gateway

- ### ERRR-503
	_Unavailable_

   Unavailable
