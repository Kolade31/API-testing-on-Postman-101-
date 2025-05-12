# API Test Case for JSONPlaceholder

### Test ID
    5
### Test Scenario
    Delete a Post.
### Description
    Verify that the API allows the deletion of a post.
### Endpoint 
    'DELETE/https://jsonplaceholder.typicode.com/posts/30'
### Expected Result
    The response body should be empty. Subsequent requests to retrieve the deleted post should return a 404 Not Found status.
### Status Code: 
    '200 OK
### Actual Result
       The response body was empty. Butsubsequent requests to retrieve the deleted post was successful as I am using a mock API.
