# Use the smaller Alpine-based Python image
FROM python:3.9-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the application code
COPY app.py /app/

# Set app.py as the entry point for the container
ENTRYPOINT ["python", "app.py"]