FROM python:3.9
ENV PYTHONUNBUFFERED 1

ARG SECRET_KEY
ARG ALLOWED_HOSTS
ARG CORS_ORIGIN_WHITELIST

ARG ALLOWED_HOSTS
ARG CORS_ORIGIN_WHITELIST

ARG POSTGRES_TABLE_NAME 
ARG POSTGRES_USER 
ARG POSTGRES_PASSWORD 
ARG POSTGRES_HOST 
ARG POSTGRES_PORT

ENV SECRET_KEY $SECRET_KEY
ENV ALLOWED_HOSTS $ALLOWED_HOSTS
ENV CORS_ORIGIN_WHITELIST $CORS_ORIGIN_WHITELIST

ENV ALLOWED_HOSTS $ ALLOWED_HOSTS
ENV CORS_ORIGIN_WHITELIST $ CORS_ORIGIN_WHITELIST

ENV POSTGRES_TABLE_NAME $POSTGRES_TABLE_NAME
ENV POSTGRES_USER $POSTGRES_USER
ENV POSTGRES_PASSWORD $POSTGRES_PASSWORD
ENV POSTGRES_HOST $POSTGRES_HOST 
ENV POSTGRES_PORT POSTGRES_PORT

WORKDIR /django
COPY requirements.txt requirements.txt

RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt
COPY . .