#Movierec 
is a movie recommender system. The basic description of the system is provided below:
The application is a catalog of movies of different genres. Each movie has a title, description, film director, list of actors, and image(s) from the main playbill. Each movie is categorized into one or more genres. Only the administrator can create, remove and update the list of movies. Users can rate the movies according to different criteria. The main feature of the system is that users can pick one movie and get the list of similar movies and/or movies that were liked the most by other users watching the same movie .

#For backend:
Designed and implemented a MYSQL database (provided  ERD, DDL and DML scripts).
Designed and implemented backend service using springboot(on top of the database).
The backend is separate for data layer, service layer, and rest layer .
documented REST API appropriately using Swagger(http://localhost:8080/swagger-ui.html).
written test cases to verify the functionality (considered corner cases).

#For frontend:

Designed a mockups of the system (screens with application possible look-in).
Used angular libraries/frameworks for the system.
Implemented services (focused on design, responsivity, meaningful routes, etc.).

#How to set up database:
please checkout Doc folder to get all DDL, DML command with ER Diagram

#How to run the backend:
Open the MovieRecommender folder in any IDE(eg. Intellij idea).
run MovieRecommenderApplication.java from src/main folder.
your application should be running on http://localhost:8080.

#How to run frontend:
for frontend service checkout the README.md file inside UI_MovieRecommender/movie-recommend/README.md

#For Application Snapshots:
Refer to this folder Doc/mockup_ui.pdf
