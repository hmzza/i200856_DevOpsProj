FROM python3.9

COPY requirements.txt .

RUN pip install Flask

COPY app.py .

CMD ["python", "app.py"]