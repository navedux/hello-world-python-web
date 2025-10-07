# Hello World Python Web Application

A simple Flask web application that returns "Hello World!" and runs on port 3000.

## Description

This is a minimal Flask web application designed to demonstrate a basic web server setup in Python. The application serves a simple "Hello World!" message on the root endpoint.

## Features

- Simple Flask web server
- Returns "Hello World!" message
- Runs on port 3000
- Accessible on all network interfaces (0.0.0.0)
- Debug mode enabled for development

## Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/navedux/hello-world-python-web.git
cd hello-world-python-web
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:3000
```

You should see the "Hello World!" message displayed.

## Project Structure

```
hello-world-python-web/
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
└── README.md          # Project documentation
```

## Configuration

The application is configured with the following settings:
- **Host**: 0.0.0.0 (accessible from all network interfaces)
- **Port**: 3000
- **Debug Mode**: Enabled

## Dependencies

- Flask==3.0.0

## Development

To modify the application:
1. Edit `app.py` to change the behavior
2. The debug mode is enabled, so changes will auto-reload
3. Access the application at http://localhost:3000

## License

This project is open source and available for educational purposes.

## Author

navedux
