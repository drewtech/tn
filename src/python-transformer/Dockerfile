FROM python:3.7.9-slim
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python3", "transformer.py"]