## Question 1

Session Authentication is the default api authentication for Django.

## Question 2

`--auth` utilizes the Basic Authentication to establish the user in secure session.

## Question 3

Session Authentication establishes authentication for the duration of the session, such that any requests that the user sends during the session includes authentication.
Token Authentication generates a token for the user to include in their requests that authenticates them till the expiration of the token, thus it does not relay on the connection remaining active.
Both schemes are better than Basic Authentication since BasicAuth requires the user's username & password in every request.

## Question 4

BitBucket sends an Authorization Grant Token to the client, who then requests from Google an Access Token using the said Grant Token. The Access Token is used to acess the user's Google account info.

## Question 5

link
