FROM python:latest

WORKDIR /app

# Néhány új réteg
RUN touch allomanysz1.txt
RUN echo "hello" > allomanysz1.txt
RUN mkdir -p /app/proba

COPY . /app

CMD ["python", "main.py"]
