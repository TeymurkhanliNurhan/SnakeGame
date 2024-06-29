# Use the official Python image as base
FROM python:3.10-slim

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file into the container at /app
COPY requirements.txt /app/

# Install any dependencies specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the entire project directory into the container at /app
COPY . /app/

# Expose port 5000 to allow communication to/from server
EXPOSE 5000

# Command to run the Flask application
CMD ["python", "app.py"]

#IN BASH/TERMINAL
# Building the Docker Image:
# docker build -t snake-game .
#
# Running the Docker Container:
# docker run -d -p 5000:5000 snake-game
#
# Pulling an Image (if the image is hosted on DockerHub, for example):
# docker pull your-username/snake-game
#
# Pushing an Image (if you want to share your image on DockerHub):
# docker push your-username/snake-game
#
# Listing Running Containers:
# docker ps
#
# Listing Docker Images:
# docker images
#
# Stopping a Container:
# docker stop app
#
# Removing a Container:
# docker rm app
#
# Removing a Docker Image:
# docker rmi image_id
