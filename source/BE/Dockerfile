FROM python:3.10.10

ENV PYTHONUNBUFFERED 1

RUN mkdir /BE

WORKDIR /BE

COPY . .

RUN pip install -r requirements.txt

RUN adduser iop
USER iop

CMD ["python", "manage.py", "runserver"]