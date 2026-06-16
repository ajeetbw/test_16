# Task Management and Data Pipeline System
## Overview
The Task Management and Data Pipeline System is a comprehensive solution that integrates a task management system, a data pipeline module, and a web API server. This system is designed to demonstrate a complete, self-contained enterprise task management system, a data extraction, transformation, and loading (ETL) pipeline, and a RESTful web API server.

## Description
The Task Management System is built using Java and utilizes object-oriented programming principles, concurrency structures, and advanced Java features. The Data Pipeline Module is implemented in Python and simulates a data ETL pipeline, generating mock sales data, aggregating metrics, and outputting the results. The Web API Server is built using Node.js and provides a complete RESTful router, error handling, and an in-memory database.

## Tech Stack
* **Programming Languages:** Java, Python, C, C++, JavaScript
* **Frameworks and Libraries:** Java Util, Java Time, Python Logging, Python Dataclasses, Node.js HTTP, Node.js URL
* **Tools:** Makefile

## Directory Structure
```markdown
.
├── TaskManagementSystem.java
├── StringProcessor.cpp
├── data_pipeline.py
├── file_io.c
├── main.c
├── item.h
├── server.js
├── inventory.h
├── file_io.h
├── Makefile
├── utils.c
├── utils.h
├── item.c
└── inventory.c
```

## Installation and Startup
1. Clone the repository: `git clone https://github.com/your-repo/TaskManagementSystem.git`
2. Navigate to the project directory: `cd TaskManagementSystem`
3. Compile the Java code: `javac TaskManagementSystem.java`
4. Compile the C and C++ code: `make`
5. Start the Node.js server: `node server.js`

## Usage
### Task Management System
* Create a new task: `Task task = new Task(1, "Task Title", "Task Description", TaskPriority.HIGH);`
* Update task status: `task.setStatus(TaskStatus.IN_PROGRESS);`
* Print task details: `System.out.println(task.toString());`

### Data Pipeline Module
* Generate mock sales data: `DataPipeline pipeline = new DataPipeline(); pipeline.generate_data();`
* Process and aggregate data: `pipeline.process_data();`

### Web API Server
* Get all users: `GET /users`
* Get user by ID: `GET /users/:id`
* Create new user: `POST /users` with JSON payload `{"name": "John Doe", "role": "Admin"}`

## Contributing
Contributions are welcome! Please submit a pull request with your changes and a brief description of the updates.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.