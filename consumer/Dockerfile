FROM python:3.7-slim

ENV PYTHONDONTWRITEBYTECODE=1

RUN pip3 install kafka-python

COPY consumer .


CMD ["python3", "-u", "./consumer.py"]