FROM python:3.8-slim

WORKDIR /weather-service

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

CMD ["python", "weather.py"]
