FROM python:3.6-alpine

WORKDIR /usr/src/app
RUN apk add --no-cache build-base
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY main.py main.py

CMD ["python3","-u","main.py"]

