# Use the official Python slim image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements.txt into the container
COPY requirements.txt requirements.txt

# Install the dependencies
RUN pip install -r requirements.txt

# Copy the rest of your application code
COPY . .

# Command to run the Flask app
CMD ["python", "app"]
