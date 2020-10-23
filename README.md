# Marlabs


Gemini Health is a provider of medical database integration system. 

My responsibility for this project is to use spring boot for the migration to the microservices architecture.
The migration includes generating different modules for the medical database integration system such as personal info modules, search alternative medicines products modules and find nearby pharmacy stores and medicines modules. 
I then used Spring cloud netflix, eureka, hytrix for checking the health of the microservices and fallback methods.
For security, I used jwt with saml for authetification and authorization with single sign on that allows users with different roles could access different resources.
for database that stores the information of users and products, I used hibernate with mysql database.
for front end, I used Angular for the single page application and html, css and bootstrap.
To inform the customers with the medicines information that they are interested in, I use kafka for the messaging system which would pass the messages to different customers.
The project follows TDD and agile development. I use Jira for bug tracking and jenkins for CICD pipeline.
