
# Sankalp API

This documentation provides a detailed overview of the Sankalp API, available endpoints, authentication, error handling, and additional details. 
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

Backend

`MONGO_URI`
`SECRETKEY`
`ORIGIN`

## Endpoints

#### *Authentication*
Signup: POST /auth/signup\
Login: POST /auth/login\
Logout: GET /auth/logout\
Token Refresh: GET /auth/refresh
#### *Lists*
Get All Lists: GET /lists/:userId\
Create List: POST /lists\
Update List: PUT /lists/:listId\
Delete List: DELETE /lists/:listId
#### *Tasks*
Add Task: POST /tasks\
Delete Task: DELETE /tasks/:listId/:index\
Toggle Task Completion: PUT /tasks/toggle
## Authors

[@mohakcodes](https://www.github.com/MOHAKCODES)

