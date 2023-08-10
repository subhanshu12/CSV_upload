# CSV_Upload
CSV_Upload is a web application that allows users to upload and parse CSV files. The application is built with Node.js and Express, and it provides a simple and user-friendly interface for managing CSV data.

## Installation
To install CSV_Upload, please follow these steps:

Clone this repository using the following command:
```
$ git clone https://github.com/subhanshu12/CSV_upload
```
Install the required dependencies using the following command:
```
$ npm install 
```
Start the application using the following command:
```
$ npm start 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:8000 
```

## Features
* CSV file upload: Users can upload CSV files with a simple web form.
* CSV parsing: The application parses the CSV data and displays it in a table.
* Searching: Users can search data in the table.

## API Reference
CSV_Upload provides a simple API for uploading and parsing CSV files. The API supports the following endpoints:

* POST /upload: Uploads a CSV file and parses the data.
* GET /data: Returns the parsed CSV data as JSON.

## Folder Structure
```
CSV_Upload/
|── |assets/
│   |      ├── css/
│   │      |     ├── styles.css
│   |      ├── js/
│   |            ├── script.js
│   ├── uploads/
│   ├── index.html
|   |
├── routes/
│   ├── csvRoutes.js
|   |
├── controllers/
│   ├── csvController.js
|   |
├── models/
│   ├── csvModel.js
|   |
├── .gitignore
├── package.json
├── README.md

```
## Screenshots
<img width="1078" alt="Screenshot 2023-08-10 135851" src="https://github.com/subhanshu12/CSV_upload/assets/101986633/22498ccf-0af2-4e95-99dc-6399b0dbb3c5">
<img width="1077" alt="Screenshot 2023-08-10 135818" src="https://github.com/subhanshu12/CSV_upload/assets/101986633/161a8bc9-6f4f-4363-8f3a-09888312ee1d">
<img width="1076" alt="image" src="https://github.com/subhanshu12/CSV_upload/assets/101986633/79e8a713-d1a1-4135-859d-32152bcc40de">




By - Subhanshu Tripathi


