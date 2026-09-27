# main.py
from fastapi import FastAPI app=FastAPI()  @app.get("/") def home():     return {"message":"AI Crypto Tool"}  @app.get("/health") def health():     return {"status":"ok"}
