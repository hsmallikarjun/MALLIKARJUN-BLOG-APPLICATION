React Java Spring Boot full stack application for demonstration and educational purposes. Simple demo blog with basic functionality such as JWT
authentication, create new users and full CRUD (Create, Retrieve, Update, Delete) operations on posts and comments. Blog is pre-populated
with demo data on application start. Create new user or login with any author full name, password is `password`, administrator
username: `admin` password: `admin`.

### Installation

1. Download source code as zip, unzip archive or `git clone https://github.com/hmurij/react-spring-boot-blog.git`.
2. Navigate to `demo-blog-frontend` folder and run `npm install`

### Access the application
1. Navigate to `demo-blog-backend` and run `gradlew bootRun` to start backend Spring Boot REST API application.
2. Navigate to `demo-blog-frontend` and run `npm start` command, it will start frontend application and open main window on [http://localhost:3000](http://localhost:3000).

### Reference
* [Blog REST API documentation](./demo-blog-backend/README.md)
* [Sister project using Thymeleaf and Spring MVC](https://github.com/hmurij/thymeleaf-spring-mvc-blog)
