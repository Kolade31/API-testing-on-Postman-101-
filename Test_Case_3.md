# API Test Case for JSONPlaceholder

### Test ID
    3
### Test Scenario
    Create a New Post.
### Description
    Verify that the API allows the creation of a new post.
### Endpoint 
    'POST/https://jsonplaceholder.typicode.com/posts'
### Request Body
#### JSON

    {

      "userId": 11,
  
      "title": "Orationis serenitas",
  
      "body": "Deus, da mihi serenitatem ad accipienda quae non possum mutare, animos mutare quae possum, ac            sapientiam differentiam cognoscere."
  
    }

### Expected Result
    The response body should include the created post with the same title, body, and userId, along with a new id.
### Status Code: 
    '201  Created
### Actual Result
     The response body included the created post with the same title, body, and userId, along with a new id.
