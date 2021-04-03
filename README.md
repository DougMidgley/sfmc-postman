# sfmc-postman
Respository with extensive SFMC Postman collections
## AUTH
Authorization is managed via the Collection, using the V2 tokens (no username password supported). This requests the token for you and sets the values for reuse, plus requests new tokens once expired. 
## SOAP
SOAP requests are examples of requests, which for the most part are good examples, but the documentation available from Salesforce is patchy at best. Some objects are completely unsupported while documentation says they are. Happy to receive PRs to update

## REST
REST requests are extensively used. Many resources are not officially supported and are just based on experience/browser network request tracking.

## Internal
Many internal APIs exist, which allow more full access to the system. These are not supported and are not documented anywhere. This can be used by checking the network request for update-token.json which contains it

## SDK
Both mobile SDK and einstein predictions SDK are here also. Officially these are unsupported, so use with care
