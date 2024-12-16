# POST /send-message

## Description
Send a message to a user.

## Request Body
- Content-Type: application/json
- Body: 
  ```json
  {
    "userId": "string",
    "message": "string"
  }
  ```

## Responses
### 200 OK
- Content-Type: application/json
- Body: Confirmation of message sent.

### 400 Bad Request
- Content-Type: application/json
- Body: Error details.
