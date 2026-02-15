# Dev Container Template - Python & Django/Flask

Pre-configured containerized development environment for Python web applications using Django or Flask.

## Features

- **Python 3.11** with pip
- **Django** and **Flask** support
- **FastAPI** support
- **Black** + **isort** + **flake8** for code quality
- **pytest** for testing
- **SQLTools** + **SQLite3 Browser** for database management
- IntelliCode AI-assisted completion
- PostgreSQL support via psycopg2

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - Development server (Django/Flask)
- `5000/5001` - Flask debug mode
- `8000` - Django development server
- `8080` - Alternative HTTP server

### Extensions Included
- Python
- Pylance
- Black Formatter
- isort
- flake8
- Docker
- PowerShell
- SQLTools
- SQLite3 Browser
- IntelliCode

### Post-Create Commands
- Upgrades pip
- Installs black, isort, flake8
- Installs pytest for testing
- Installs Django, Flask, FastAPI
- Installs uvicorn, gunicorn for serving
- Installs PostgreSQL driver

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
