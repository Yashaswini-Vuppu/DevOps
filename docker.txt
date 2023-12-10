# Use an official Python runtime as a parent image
FROM python:3.9.18-alpine3.19

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Run app.py when the container launches
CMD ["python", "app.py"]

