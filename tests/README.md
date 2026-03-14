# Backend FastAPI Tests

This directory contains automated tests for the FastAPI backend, using pytest and the Arrange-Act-Assert (AAA) pattern.

## How to run tests

1. Install dependencies:
   ```
pip install -r ../requirements.txt
```
2. Run all tests:
   ```
pytest
```

## Test Structure
- All tests use the AAA pattern for clarity.
- Tests cover activity listing, registration, duplicate prevention, unregistering, and error handling.
