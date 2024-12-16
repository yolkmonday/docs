# POST /file

## Description
Upload a file.

## Request Body
- Content-Type: multipart/form-data
- Body: 
  - `file`: The file to upload.

## Responses
### 200 OK
- Content-Type: application/json
- Body: Details of the uploaded file.

### 400 Bad Request
- Content-Type: application/json
- Body: Error details.
