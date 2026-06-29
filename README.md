# Flask DevOps Lab

A diagnostic Flask application for practicing Git, GitHub, and Docker workflows.

## Usage

To run this Flask application locally, follow these steps:

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

The application will start on `http://localhost:8080`.

## API Endpoints

| Endpoint | Description |
|----------|-------------|
| `/api/health` | Returns a simple health check status |
| `/api/config` | Returns the application configuration (app name, version, targets) |
| `/api/report` | Returns system information including hostname, Python version, and uptime |

## Technologies Used

- **Flask** - Python web framework
- **Git** - Version control
- **GitHub** - Remote repository and collaboration
- **Docker** - Containerization
