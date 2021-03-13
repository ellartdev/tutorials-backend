# tutorials-backend
I followed on some tutorial on REST API and back-end development
did it with tutorial: https://bezkoder.com/node-express-mongodb-crud-rest-api/

## docs
Different methods to use. Use `/api/tutorials`

Replace `:id` with tutorial ID

### Getting all tutorials
`GET /api/tutorials`

### Getting specific post with ID
`GET /api/tutorials/:id`

### Getting all published tutorials
`GET /api/tutorials/published`

### Getting tutorials where a string contains in the title
`GET /api/tutorials?title=js`

### Posting a new tutorial
`POST /api/tutorials`

Body parameters:
- `title` - Tutorial's title
- `description` [optional] - Tutorial's description

### Updating a post
`PUT /api/tutorials/:id`

When updating, at least one parameter is required. 

Body parameters:
- `title` - Tutorial's title
- `description` - Tutorial's description
- `published` - Tutorial's state (boolean)

### Deleting tutorial with specific ID
`DELETE /api/tutorials/:id`

### Deleting all tutorials
`DELETE /api/tutorials`

#
ellartdev 2020
