FROM python:3-alpine
MAINTAINER Babu Reddy

COPY app /app

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 80

CMD ["python", "app.py"]