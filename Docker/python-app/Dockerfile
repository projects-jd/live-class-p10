# Use official Python image
FROM python:3.10-slim

# Set working directory inside container
WORKDIR /usr/src/app/

# Copy application files
COPY . /usr/src/app/

# Install dependencies (if requirements.txt exists)
RUN pip install --no-cache-dir -r requirements.txt || true

# Expose port (change if your app uses a different port)
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]

