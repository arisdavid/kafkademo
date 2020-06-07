FROM python:3.7-slim

ENV PYTHONDONTWRITEBYTECODE=1

RUN pip3 install kafka-python
RUN pip3 install faker

COPY producer .


CMD ["python3", "-u", "./producer.py"]