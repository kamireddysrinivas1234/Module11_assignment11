# FastAPI Calculations Assignment with Calculator + Coverage

Calculator web UI is at `/` and `/calc`.

## Run locally (SQLite)

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open: http://127.0.0.1:8000/

## Run tests with coverage

```bash
pytest
```

Coverage is configured in `pytest.ini` as `--cov=app --cov-report=term-missing`.

## Run with Docker Compose

```bash
docker-compose up --build
```

Then go to: http://localhost:8000/

docker link : https://hub.docker.com/repository/docker/srinivaskamireddy/fastapi_calculations_latest_factorypattern/image-management
