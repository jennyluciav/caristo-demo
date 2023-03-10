
FROM python:3.10-slim-buster
COPY requirements.txt .
RUN pip3 install -r requirements.txt
ENV PYTHONUNBUFFERED=TRUE
ENTRYPOINT ["python3"]
