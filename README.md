# Thunderstorm-Forcasting-with-MLFlow-Tracking
uv init

uv venv thenv

thenv\Scripts\activate

conda create -p thndenv python==3.13 -y

# run the application

uvicorn api.main:app --host 0.0.0.0 --port 8000

streamlit run streamlit_app\ui.py