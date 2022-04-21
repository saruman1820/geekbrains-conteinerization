FROM python:3.9

RUN mkdir /app

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT python app.py runserver 0.0.0.0:8000
