FROM python:3.9.2-buster


# pip installs
COPY ./app/python/config/requirements.txt requirements.txt
RUN pip install -r requirements.txt

WORKDIR /app