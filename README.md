# Snippetbox Project
This repository contains the code for the Snippetbox project, which is part of the "Let's Go!" book by Alex Edwards.


Snippetbox is a simple web application that allows users to create, manage, and share code snippets. It's built using the Go programming language and follows the principles and best practices outlined in the "Let's Go!" book.

## Features
- Create and store code snippets.
- Edit and delete existing snippets.
- User authentication and authorization.
- Syntax highlighting for code snippets.
- User-friendly web interface.

## Getting Started
The instructions will help you get a copy of the Snippetbox project up and running on your local machine for development and testing purposes.

### Prerequisites
- Go (version 1.16)

### Installation
1. Clone the repository to your local machine:
``` git clone https://github.com/buya023/snippetbox.git ```
2. Navigate to the project directory:
```cd snippetbox ```
4. Create a .env file in the project root directory and configure your environment variables. You can use the provided .env.example as a template.
5. Install the necessary Go dependencies:
```go mod tidy```
6. Run the application:
```go run cmd/web```
7. Access the application in your web browser at http://localhost:4000.

## Acknowledgments
Alex Edwards for the "Let's Go!" book.
The Go community for their valuable contributions.
