# ALX Files Manager

This project is a backend application that simulates a file management platform. It allows users to upload, view, and manage files. The application covers topics such as user authentication, file storage, database management, and background processing, using technologies like Node.js, MongoDB, Redis, and Express.

## Table of Contents
- [Curriculum](#curriculum)
- [Specializations](#specializations)
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Tasks](#tasks)
  - [Redis Utils](#redis-utils)
  - [MongoDB Utils](#mongodb-utils)
  - [First API](#first-api)
  - [User Management](#user-management)
  - [File Management](#file-management)
- [Resources](#resources)
- [Learning Objectives](#learning-objectives)

## Curriculum
- **Short Specializations**

## Specializations
- **0x04. Files manager**
- **Back-end**

## Project Overview

This project is a comprehensive summary of the backend trimester, focusing on the following key areas:
- User Authentication
- File management (uploading, viewing, and permission changes)
- Database management with MongoDB and Redis
- Pagination and background processing

The platform allows users to:
- Authenticate via a token
- List all files
- Upload new files
- Change file permissions
- View files
- Generate thumbnails for images

## Technologies Used

- **JavaScript (ES6)**
- **Node.js**
- **Express.js**
- **MongoDB**
- **Redis**
- **Kue (for background processing)**
- **Bull (for handling queues)**

## Features

1. **User Authentication:** Secure user login via token-based authentication.
2. **File Management:**
   - Upload files
   - List files
   - Change file permissions
   - View files
   - Generate thumbnails for image files
3. **Background Processing:** Utilizing Kue for managing background jobs like thumbnail generation.
4. **Database Management:** Persistent data storage using MongoDB and Redis for temporary data.

## Requirements

- **Editors:** vi, vim, emacs, Visual Studio Code
- **Environment:** Ubuntu 18.04 LTS
- **Node.js:** Version 12.x.x
- **ESLint:** Linting tool for JavaScript
- **Mandatory Files:**
  - `package.json`
  - `.eslintrc.js`
  - `babel.config.js`

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/LevyWanyonyi/alx-files_manager.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

To start the server, run:
```bash
npm run start-server
```

To run the development environment:
```bash
npm run dev
```

## Tasks

### Redis Utils
- Implement a Redis client to handle connections and operations with Redis.

### MongoDB Utils
- Implement a MongoDB client to handle connections and operations with MongoDB.

### First API
- Create an Express server with endpoints for checking the status of Redis and MongoDB.

### User Management
- Implement user creation, login (authentication), and user data retrieval based on tokens.

### File Management
- Implement file upload, listing, and management features. Users can upload files, and the files will be stored on the server with specified permissions.

## Resources

- [Node JS getting started](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [Process API doc](https://nodejs.org/dist/latest-v12.x/docs/api/process.html)
- [Express getting started](https://expressjs.com/en/starter/installing.html)
- [Mocha documentation](https://mochajs.org/)
- [Nodemon documentation](https://nodemon.io/)
- [MongoDB](https://docs.mongodb.com/)
- [Bull](https://optimalbits.github.io/bull/)
- [Image thumbnail](https://www.npmjs.com/package/image-thumbnail)
- [Mime-Types](https://www.npmjs.com/package/mime-types)
- [Redis](https://redis.io/documentation)

## Learning Objectives

By the end of this project, you should be able to:
- Create an API using Express
- Authenticate users and manage sessions
- Store data persistently in MongoDB
- Use Redis for temporary data storage
- Set up and manage background workers for processing jobs
