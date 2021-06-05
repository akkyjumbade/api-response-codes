# Response Codes for server

|Code|Name|Description|
|--|--|--|
|E400|INVALID_REQ|You have requested the page with some malformed or invalid parameters.|
|E401|INVALID_ACCESS|Authorization token is not authorized, check extended error message in body for more details.|
|E403|ACCESS_DENIED|Access to the page/ resource has been restricted by the admin.|
|E404|RESOURCE_NOT_AVAILABLE|This means that the url or the page you are trying to visit is not available on the  	server or it may removed from the server.|
|E405|INVALID_METHOD|You are accessing the page with wrong method. You have to check the guidelines for the API.|
|E409|RESOURCE_CONFLICT|add description|
|E410|SESSION_CLOSED|The session has expired|
|E410|REQ_LENGTH|Length Required|
|E412|PRECONDITION_FAILED|Content-Length header was required, but not provided.|
|E413|REQ_LARGE|Request Entity too Large|
|E429|TOO_MANY_REQ|Request rate limit exceeded, please try again later|
|E500|SERVER_ERROR|Internal Service Error|
|E503|SERVER_UNAVAILBLE|Unavailable|
