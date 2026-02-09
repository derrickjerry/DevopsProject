FROM python:3.8-slim

WORKDIR /alert-service

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

CMD ["python", "alert.py"]
