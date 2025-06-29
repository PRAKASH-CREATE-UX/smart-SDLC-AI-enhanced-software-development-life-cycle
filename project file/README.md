#run backend
cd project
.\venv\scripts\activate
cd backend
pip install -r requirements.txt
uvicorn --reload main:app --host 0.0.0.0 --port 8000


#run frontend
cd project
.\venv\scripts\activate
cd frontend
pip install -r requirements.txt
streamlit run app.py

