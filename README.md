# WeChat

**WeChat** is a responsive real-time chat application where users can sign up and instantly connect with friends. The application uses the following technologies and features:

## Features

- **User Registration:**: Allows new users to sign up easily.
- **Authentication**: Uses OAuth2 for user authentication and 2FA (two-factor authentication) for enhanced security.
- **WebSockets**: Implements WebSockets for real-time message delivery.
- **Advanced Search**: Uses ElasticSearch for fast and efficient searches.
- **Frontend**: Built with React and styled with Tailwind CSS for a modern and responsive interface.

## Technologies

- **Ruby**: 3.2.2
- **Rails**: 7.2.1.2

## Environment Setup

### Prerequisites

Before running the project, you need to have Docker installed on your machine. Additionally, make sure that ElasticSearch is installed and running, as the application depends on it for search functionality.

### Docker Commands

To manage the application using Docker, use the following commands:
- **Access the Docker container:**:
  ```bash
  docker-compose exec web bash


- Start the Rails console:

  ```bash
  docker-compose exec web rails console

- Stop Docker containers:

  ```bash
  docker-compose down

- Start Docker containers:

  ```bash
  docker-compose up --build

- Run tests:

  ```bash
  docker-compose exec web bundle exec rspec

- Recreate test environment:

  ```bash
  docker-compose exec web bin/rails db:environment:set RAILS_ENV=test

![Imagem 1](./1.png)

![Imagem 2](./2.png)

![Imagem 3](./3.png)

