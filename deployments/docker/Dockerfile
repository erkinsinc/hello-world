## Build the image based pyhton3
FROM python:3

## Copy all the packages
COPY . /app

## Change the default folder
WORKDIR /app

## Install all packages
RUN pip install -r /app/requirements.txt 


## Default port is 5000
EXPOSE 5000

## When container is started puthon app.py
CMD ["/bin/sh", "-c", "python /app/app/py"]