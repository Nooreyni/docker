# importing the python image from dockerhub
FROM python:3.8
# running app directory to store copied file
RUN mkdir /app
# copying the pipeline directory 
# wich store the subdirectory for the python files
COPY pipeline/ app/pipeline/
#requirement wich contain modules needed to run python files
COPY requirements.txt /app/requirements.txt
# working directory in our container
WORKDIR /app
# installing requirements needed
RUN pip3 install -r requirements.txt
# command to execute 
CMD ["python", "model.py"]
