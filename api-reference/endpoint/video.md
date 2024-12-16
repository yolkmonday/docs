# POST /video

## Description
Upload a video.

## Request Body
- Content-Type: multipart/form-data
- Body: 
  - `file`: The video file to upload.

## Responses
### 200 OK
- Content-Type: application/json
- Body: Details of the uploaded video.

### 400 Bad Request
- Content-Type: application/json
- Body: Error details.
