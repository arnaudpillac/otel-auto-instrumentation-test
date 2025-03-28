# Use a minimal Python image
FROM python:3.9

WORKDIR /app

# Copy application files
COPY app.py /app/

# Install dependencies
RUN pip install flask

# Expose port 5000
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
