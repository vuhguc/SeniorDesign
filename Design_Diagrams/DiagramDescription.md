# Diagram Description

## Convention
Already included in each diagram

## Function of each element
(The mentioned components are all from D2 diagrams)
* Authenticate layer: a layer to take username and password from user and check whether all information is correct
If the information is correct, let them join in their account and use our service
The authenticate layer is currently 6+2 authentication from UC but might be changed later

* HTML components: the place where the user will use our service and interact with our database

* Article database: where we store our pre-processed article. We take articles from reliable sources such as Pubmed

* Search layer: the code where we put the logic of elastic search. It will receive input such as keyword and focus
from the user, perform elastic search on pre-processed database and return the articles


* Interaction database: the database where we save the user interaction from record layer

* Record layer: the code where we put the logic of user interaction. The recorded interaction will be mainly
their clicks and where they happen. Those data will be used as sample data for later UI research


