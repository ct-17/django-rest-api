FROM python:3.10.10

ENV PYTHONUNBUFFERED 1

RUN mkdir /BE

WORKDIR /BE

COPY ./source/BE .

RUN pip install -r /requirements.txt

RUN adduser -D iop
USER iop