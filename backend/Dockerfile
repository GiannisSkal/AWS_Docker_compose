FROM python:3.7-alpine 
WORKDIR /app 
COPY requirements.txt /app
RUN pip3 install -r requirements.txt 
COPY main.py /app/main.py
COPY wsgi.py /app/wsgi.py

