Here is a `README.md` for your real-time chat application:

```markdown
# Real-Time Chat Application

This is a real-time chat application built with Java, Spring Boot, and MongoDB. It allows users to send and receive messages in real-time.

## Features

- User registration
- Real-time messaging between users
- Chat room creation and management

## Technologies Used

- Java
- Spring Boot
- MongoDB
- Maven

## Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher
- MongoDB

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Ovtt17/Realtime-Chat-Application.git
cd Realtime-Chat-Application
```

### Configure MongoDB

Make sure MongoDB is running on your local machine or configure the `application.properties` file to point to your MongoDB instance.

Alternatively, you can use docker-compose to set up MongoDB:

```bash
docker-compose up -d
````

This will start a MongoDB and MongoExpress instance in a Docker container. Make sure to complete the setup by adding your own credentials in the `docker-compose.yml` file.

### Build the Project

```bash
mvn clean install
```

### Run the Application

```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8080`.

## API Endpoints

### User Endpoints

- `POST /users/register` - Register a new user
- `POST /users/login` - Login a user

### Chat Room Endpoints

- `GET /chatrooms` - Get all chat rooms
- `POST /chatrooms` - Create a new chat room

### Message Endpoints

- `GET /messages` - Get all messages in a chat room
- `POST /messages` - Send a new message

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
```

This `README.md` provides an overview of the project, instructions on how to set it up and run it, and a brief description of the available API endpoints.