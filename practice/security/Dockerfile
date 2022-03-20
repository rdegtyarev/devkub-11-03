FROM python:3.9-alpine

# Install security app
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY src ./

CMD [ "python", "./server.py" ]
