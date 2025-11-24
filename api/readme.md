# Example API from Database

Created step-by-step in the book Hands-on APIs for AI and Data Science

## Quick Start

    pip3 install -r requirements.txt
    fastapi run main.py


## Project Structure

- `main.py` - The SportsWorldCentral main FastAPI file
- `requirements.txt` - Project dependencies
- `crud.py` - Helper methods to retrieve data from the database
- `database.py` - Configuration settings for database session
- `fantasy_data.db` - SQLite database containing the API's data
- `schemas.py` - Pydantic models to validate data structures
- `models.py` - SQLAlchemy data structures

- `requirements.txt` - Project dependencies

## Learn More

- [API Prácticas para IA y ciencia de datos](https://handsonapibook.com/es/)



## Tests

Test the crud.py interaction with the database:
    
    pytest test_crud.py 

Test the API code (you don't have to run the API separately, this will run the API during testing):
    
    pytest test_main.py 
