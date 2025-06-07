# AI in Arabic - Dictionary

A web based service to host and serve English to Arabic translations of termonologies related to artificial Intelligence  and machine learnibng.

## Local Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Unix/macOS
# or
.\venv\Scripts\activate  # On Windows
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Install pre-commit hooks (first time only):
```bash
pre-commit install
```

4. Run the application:
```bash
python run.py
```


## Testing
Unit tests are defined within /tests folder. We use pytest as a tesring framework. You can run the tests using:

```bash
pytest
```
