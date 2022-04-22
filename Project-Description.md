# Project Description
#### Team name: gameisez
#### Members
* Hoang Vu
  * Computer Science
  * vuhg@mail.uc.edu

* Khanh Le
  * Computer Science
  * lekq@mail.uc.edu

#### Project Topic Area
* Our project aims to develop a web-search application on a medical document database and collect user interactions and feedbacks to boost the search algorithm.

#### Project Abstract (updated)
The ongoing fight against COVID-19 pandemic creates the need to discover, to accumulate, and to share scientific literature among physically apart members within research teams. Therefore, it becomes more critical to design a tool which can integrates a search engine on medical articles and provides the ability for all users to interact with shared resources. For this purpose, we decided to create COVID-19 Intelligent Query System (COVID-IQS). The system includes a text-based search engine using Elasticsearch for users to perform searching on our preprocessed article database. We also collect users' interactions and feedbacks to research user needs and improve our search algorithms with machine-learned ranking techniques. In addition, COVID-IQS allows the users to host a shared project, invite other users, and assign roles and privileges to all project members. The successful implementation of the COVID-IQS can support knowledge discovery and hypothesis generation in our institution and can be shared with other institutions to make a broader impact 

Problem statement: there is a need for a search engine for medical documents with reliable source for both informational and research purpose

#### Inadequacy of the current solutions to our problem 
* Available solutions in the market: There is a lack of search engine that is dedicated to medical articles only.
Most of current search engine is good at collecting articles with general knowledge but not so great for scienticfic
articles. The search result is usually mixed with personal opinions or forum discussion and is not a good point for 
referrence. We need a search engine that is built only on reliable database from approved scientific organizations.
* Available solutions within our team: our team had attempted to create COVID-19 IQS before, but there are mutliple issues
within it. In terms of backend development, with the current design, the database has to be pre-processed for a long period 
(which is from 1 week - 4 weeks). That might be costly whenever we want to update our article databases. In terms of frontend
design, the current design is very difficult to maintain. Hard code and repeated HTML code blocks are very common. The frontend design
is also not suitable as the scope of our project is growing faster.

####  Technical background applicable to problem
* Flask app with Python
* Web frontend design with HTML, Bootstrap, CSS, jQuery, javascript
* MySQL to query the database
* Elastic search


 #### Project team approach to problem
* Implement a dynamic programming approach for processing data. Only a part of data will be pre-processed. The remains could be processed
later based on the user's request
* Modularize code layer and HTML templates. We try to create a OOP-alike environment for HTML templates