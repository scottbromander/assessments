# Full Stack Challenge - Full Stack MEAN

### Recommended Time: 4 hours
### Recommended Time at Prime Academy: Tier 2, Week 7

### Topics
#### Node / Express
- Server Setup 
- Routing
- Request Params
- Request Body
- CRUD to Database

#### Mongo
- Setup 
- Create
- Read
- Delete

#### AngularJS
- Apps
- Controllers
- ng-repeat
- ng-click
- Inputs and Business Logic
- HTTP requests
- Basic Filtering

## Application
In this challenge, you will be creating a full stack application that will be used for accepting Employee information.

#### Requirements
- Application needs to load with any existing entries to the Database written to the DOM.
- Application needs to have an inputs for `name`, `position`, and `income`.
- Application needs to have a button to submit an entered employee.
- The entered employee should be sent to the database. When successfully written, the application should make a second call
to the server to get an updated employee list.
- When listing an employee, you need to list their `name`, `position`, `income`, as well as a delete button.
- The delete button for the employee should remove the employee from the Database. Once that delete is complete, the 
application should get the most current employee list (now with the employee deleted removed from the list). 
- Application needs to show the income total above the employee list. This should update correctly when an employee is 
deleted or added. 
- `Income` should always be formatted for USD currency.

Image below reflects shows how the application should function:
![Gif showing application functionality](https://media.giphy.com/media/3o8dFAZJ0BPvjJHcis/giphy.gif)
