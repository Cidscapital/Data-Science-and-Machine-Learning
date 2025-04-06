# Fast-API-ML-Web

Fast-API-ML-Web is a web application built using FastAPI to serve machine learning models. It provides a RESTful API for making predictions and managing the ML model lifecycle.

## Features

- **FastAPI Framework**: High-performance API framework for Python.
- **Machine Learning Integration**: Serve ML models for predictions.
- **Scalable**: Easily extendable for additional endpoints or models.
- **Interactive API Documentation**: Auto-generated Swagger UI and ReDoc.

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Cidscapital/Fast-API-ML-Web.git
   cd Fast-API-ML-Web
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

2. Open your browser and navigate to:
   - Swagger UI: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
   - ReDoc: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

3. Use the API to send requests for predictions or other operations.

## Project Structure

```
Fast-API-ML-Web/
├── main.py                # Entry point for the FastAPI application
├── models/                # Directory for ML models
├── routes/                # API route definitions
├── utils/                 # Utility functions
├── tests/                 # Unit and integration tests
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## API Endpoints

- **GET /**: Health check endpoint.
- **POST /predict**: Send input data to get predictions from the ML model.

## Testing

Run the test suite using `pytest`:
```bash
pytest
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Uvicorn Documentation](https://www.uvicorn.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/)

