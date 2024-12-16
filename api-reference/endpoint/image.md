# POST /image

## Description
Upload an image.

## Request Body
- Content-Type: multipart/form-data
- Body: 
  - `file`: The image file to upload.

## Responses
### 200 OK
- Content-Type: application/json
- Body: Details of the uploaded image.

### 400 Bad Request
- Content-Type: application/json
- Body: Error details.
