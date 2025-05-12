# API Test Case for JSONPlaceholder

### Test ID
    4
### Test Scenario
    Update an Existing Post.
### Description
    Verify that the API allows updating an existing post.
### Endpoint 
    'PUT/https://jsonplaceholder.typicode.com/posts/100'
### Request Body
#### JSON

    {
    "userId": 10,
    
    "id": 100,
    
    "title": "Invocatio ab actore ad sapientiam",
    
    "body": "Deus, da mihi serenitatem ad accipienda quae non possum mutare, animos mutare quae possum, ac     
     sapientiam differentiam cognoscere."
    }

### Expected Result
    The response body should match the updated post, reflecting the changes in title and body.
### Status Code: 
    '200 OK
### Actual Result
      The response body matched the updated post, reflecting the changes in title and body.
