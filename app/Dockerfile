# Use the Python 3.8 image as the base
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy application files into the container
COPY . .

# Install the required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the Flask application's port
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
