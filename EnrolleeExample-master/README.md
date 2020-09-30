# Project Name: EnrolleeExample 
 SpringBoot Microservice 

# The challenge
Spring Boot  and your database of choice (PostgreSQL, MySQL, MongoDB -- any you'd like), develop a microservice for tracking the status of enrollees in a health care program.
- Enrollees must have an id, name, and activation status (true or false), and a birth date
- Enrollees may have a phone number (although they do not have to supply this)
- Enrollees may have zero or more dependents
- Each of an enrollee's dependents must have an id, name, and birth date

The application we will be building will need to be able to do these things:
- Add a new enrollee
- Modify an existing enrollee
- Remove an enrollee entirely
- Add dependents to an enrollee
- Remove dependents from an enrollee
- Modify existing dependents


#Notes
- Click run and wait for project to be built
- Go to http://localhost:8080/h2-console/ for Database. You can check data in tables here.
- Username is "sa" and password is "1234"
- Go to http://localhost:8080/swagger-ui.html#/dependent45enrollee45rest45controller
- You will find apis here. Fill necessary fields and click Try it out
- You can check result in DB and see new data
