#Use python as the base image
FROM python:3.9

#Set the working directory inside the container
WORKDIR app/

#Copy the application file into the container
COPY app.py .

#Install Flask using pip
RUN pip install Flask

Run the Flask application when the container starts
CMD ["python","app.py"]