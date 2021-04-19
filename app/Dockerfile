FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
COPY templates /app/templates

RUN pip install -r requirements.txt

COPY app.py /app
CMD python app.py