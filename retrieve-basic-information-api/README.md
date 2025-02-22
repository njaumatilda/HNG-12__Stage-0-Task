# HNG Stage 0 API
This is a simple REST API project that provides a single GET endpoint which returns specified user information in JSON format.

## Features 
+ Provides my HNG registered email
+ Provides current datetime in ISO 8601 format which is dynamically generated
+ Provides GitHub repository URL
+ Returns response in JSON format
+ Handles CORS for cross-origin requests

## Tech Stack
+ Node.js
+ Express.js 

## Local setup instructions
1. Clone the repository

```bash
git clone https://github.com/njaumatilda/HNG-12__Backend-Development-Internship/
```

2. Navigate to the project directory

```bash
cd HNG-12__Backend-Development-Internship/
```

3. Navigate to the project subdirectory

```bash
cd retrieve-basic-information-api/
```

4. Install dependencies

```bash
npm install
```

5. Configure environment variables

To run this project, you will need to create a `.env` file in the project directory and make sure it is included in the `.gitignore` file. Configure the following environment variables:

```env
PORT = your-port
```

> Replace `your-port` with your specified port

6. Start the server

```bash
npm start
```

## API Documentation
Here is the reference on the usage of the API: 
[API Documentation](https://documenter.getpostman.com/view/38132076/2sAYX5K2mA)

## Deployment
The API has been deployed to a publicly accessible endpoint on Vercel:
[Live URL](https://hng-12-backend-development-internship.vercel.app/)

## Author
[Matilda Njau](https://github.com/njaumatilda) - 
[Node.js Backend Developer](https://hng.tech/hire/nodejs-developers)


