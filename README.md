# FastAPI MongoDB REST API
## Setup env

- **virtualenv venv
  For Linux/Mac

- **source venv/bin/activate
  For Windows

  source venv/Scripts/activate

-**Install package
  Save Dependencies to requirements.txt (optional):
  You can save the installed dependencies to a requirements.txt file for easier management and sharing with others.
pip freeze > requirements.txt


  pip install fastapi pymongo uvicorn
  
- **Start server

  uvicorn index:app --reload
