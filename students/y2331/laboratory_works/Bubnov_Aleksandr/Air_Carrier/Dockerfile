FROM python:3.8.5

ENV PYTHONUNBUFFERED 1

RUN mkdir /code
WORKDIR /code
COPY req.txt /code/
RUN pip install -r req.txt

COPY ./manage.py ./
COPY ./Air_Carrier ./Air_Carrier
COPY ./app ./app
COPY ./templates ./templates
COPY ./db.sqlite3 ./


