FROM python:3.9

WORKDIR /app

ADD . /app
RUN pip install -r requirements.txt


EXPOSE 8000

ENTRYPOINT python /app/app.py runserver 0.0.0.0:8000