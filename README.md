# Vocab Cards

A simple but effective platform for studying, reviewing, and memorizing vocabulary with a clean, Notion-like interface.

## Features

- Create and manage vocabulary cards with words, meanings, examples, and context notes
- Organize cards into folders/collections
- Clean, minimal UI inspired by Notion
- Easy to use for personal learning
- Docker support for easy deployment

## Development

This project is currently in development.

## Docker Setup

### Using Docker Compose (Recommended)

1. Make sure you have Docker and Docker Compose installed on your system
2. Clone this repository
3. Run the application:

```bash
docker-compose up -d
```

4. Access the application at http://localhost:8080

### Using Docker directly

1. Build the Docker image:

```bash
docker build -t vocab-cards .
```

2. Run the container:

```bash
docker run -p 8080:80 -d vocab-cards
```

3. Access the application at http://localhost:8080

### Development with Docker

For development with live-reloading of changes:

```bash
docker-compose up
```

This will mount your local index.html file into the container, so any changes you make will be immediately reflected.