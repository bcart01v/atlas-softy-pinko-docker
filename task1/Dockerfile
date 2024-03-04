# Back-End
# Set the platform, use the same Python version as my local
FROM --platform=$BUILDPLATFORM python:3.8-slim-buster AS codebase

# Update and install dependencies 
RUN apt-get update && apt-get -y install python3-pip

# Install Flask (What is that?) using pip3 (Nightmares)
RUN pip3 install flask

# Change the directory
WORKDIR /app

# This is like T1 intro all over again!
# Copy current  codirectoryntents into 'container'
COPY . /app

# Show the port Flask will run on
EXPOSE 5252

# Setup finished, run it.
CMD ["python3", "api.py"]