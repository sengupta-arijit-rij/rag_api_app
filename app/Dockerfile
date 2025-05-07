FROM python:3.10-slim

# Copy app files
WORKDIR /app

# Install Python requirements
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . /app

# Run the app
CMD ["python", "app.py"]
