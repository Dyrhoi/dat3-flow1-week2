# The HTTP Protocol

## Monitoring HTTP Headers 1
We will notice that the first time we hit the page, we get the status code 200.
However if we refresh the page we will receive status 304 which implies that the page has been cached and the client does not need to retransmit the requested source.  

## Monitoring HTTP Headers 2
We notice the same thing happening when we add images and stylesheet. First we get 200 request, then we receive 304 requests. The stylesheet however also gets cached locally and gets loaded from memory instead.

## Monitoring HTTP Headers 3
We notice we receive a 302 status request, which means we were redirected. After than we load the r.html page which gives us the status 200 code. The browser knew where to redirect us to, as it was requested by redirect.

## 3a) Redirecting to HTTPs instead of HTTP
We get redirected from the unsecure HTTP to the secure HTTPS.

## 4a) Status Codes (5xx)
We get error code 500, which means something went wrong with the server handling the request. Due to our Tomcat server we are actually told what went wrong, in this case: / by zero, division by zero.

## 4b) Status Codes (4xx)
We receive a 404 error. Which means the requested resource could not be found.

## 4c) Status Codes - Ranges
2xx - OK.  
3xx - Redirect/Cache.  
4xx - Invalid request/missing resource.  
5xx - Server error.

## 5) Get HTTP Request Headers on the Server
Added on /request

## 6) Get/Post-parameters
Get parameters are sent to the URL, so all data will be stored in the URL.  
Post parameters are sent with the header information.  
Added on /post.html

## 7) Sessions (Session Cookies)
The browser has a cookie with our session token. This token will check with the server if we currently have any data stored on the server and will return it if that is the case.
