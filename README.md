# File Metadata Microservice

A RESTful API built with Node.js and Express as part of the FreeCodeCamp curriculum. This API allows users to upload files and receive metadata information about the uploaded files.

## Features

- Upload a file through a web interface
- Receive file metadata (name, type, and size) in the JSON response

## Dependencies
1. Express
2. Multer
3. dotenv
4. cors

## API Endpoint

### Upload a file and receive metadata

`POST /api/fileanalyse`

Form field:

- `upfile`: File input field

Response:

{
"name": "uploaded_file_name",
"type": "uploaded_file_mimetype",
"size": uploaded_file_size_in_bytes
}

## Setup and Installation

1. Clone the repository:

git clone https://github.com/yourusername/file-metadata-microservice.git

2. Install dependencies:

cd file-metadata-microservice
npm install

3. Run the server:

npm start

The server will start on port 3000 or the port specified in the `PORT` environment variable.

## License

This project is licensed under the MIT License.
Make sure to replace any placeholder information (like GitHub repository URL, your username, etc.) with your own information. Once you have edited the README.md file, you can add it to your Git repository and push it to GitHub:

