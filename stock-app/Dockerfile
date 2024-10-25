FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt /app/

RUN pip install -r requirements.txt

COPY app.py /app/
COPY static /app/static/
COPY templates /app/templates/

EXPOSE 8000
EXPOSE 5001

CMD ["python", "app.py"]