FROM python:3.10.6

ENV PYTHONUNBUFFERED 1

WORKDIR /app

RUN mkdir raouf

RUN cd raouf

RUN mkdir  sofien

RUN cd sofien


COPY requirements.txt . 
RUN apt-get update

RUN pip install -r requirements.txt

COPY test.py . 

