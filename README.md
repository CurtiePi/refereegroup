# refereegroup
App to keep track of referees and their availabilty

Entities
Referee
* lname - string
* fname - string
* dob   - date
* city  - string
* country - string
* email - string
* phone - string
* level - string

Fixture
* hclub - string
* aclub - string
* city  - string
* country - string
* date  - date
* referee - string
* expenses_offered - boolean


Availability
* date - date
* referees - string[]
