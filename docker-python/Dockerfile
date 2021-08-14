FROM tiangolo/uwsgi-nginx-flask:python3.6
LABEL org.opencontainers.image.authors="info@cloudgeeks.ca"

COPY requirements.txt /tmp/
COPY ./app /app

RUN pip install -U pip && pip install -r /tmp/requirements.txt

EXPOSE 80

