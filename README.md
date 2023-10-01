# Blog Analytics with Express and Lodash
Creating a robust blog analytics and search tool using the power of Express.js and Lodash. Our objective is to craft a middleware solution that not only meticulously processes data fetched from a third-party blog API (as demonstrated in the supplied curl request) but also furnishes users with rich statistical insights. Furthermore, our tool offers a seamless blog search feature, enhancing the overall user experience.

# Table of Contents
Introduction
Usage
Getting Started
Running the Application
API Endpoint
Dependencies
Contributing
License

# Introduction
This project aims to develop a blog analytics and search tool using Express.js and Lodash. It involves creating a middleware that fetches data from a third-party blog API and provides statistics to clients. Additionally, a blog search endpoint is implemented to allow users to search for specific blog posts.

# Usage
# Getting Started
To get started with this project, follow these steps:

1.Clone the repository:
```bash
git clone https://github.com/TanujManikyala/A-Blog-Analytics-And-Search-Tool-Using-Express.js-And-Lodash.
cd A-Blog-Analytics-with-Express-and-Lodash

```

2. Install the project dependencies:

```bash
npm install

```
# Running the Application
To run the application, use the following commands:

```bash
docker build --tag blog-analytics .
docker run -d -p 7050:7050 blog-analytics

```
This will build and run the Docker container for the blog analytics application.

# API Endpoint
The main API endpoint for retrieving blog data is:

```bash
GET /api/rest/blogs

```

You can access this endpoint with the provided curl request:

```bash
curl --request GET \
  --url https://intent-kit-16.hasura.app/api/rest/blogs \
  --header 'x-hasura-admin-secret: 32qR4KmXOIpsGPQKMqEJHGJS27G5s7HdSKO3gdtQd2kv5e852SiYwWNfxkZOBuQ6'

```
# Dependencies
List any external dependencies or libraries used in your project.

Express.js
Lodash
Make sure to include the necessary dependencies in your package.json file.

# Contributing
If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure the code is well-documented.
4. Test your changes thoroughly.
5. Create a pull request, clearly describing the changes you've made.

# License
Specify the license under which your project is distributed. You can use common open-source licenses like MIT, Apache, or GNU GPL. Include the full text of the license or a link to it.


