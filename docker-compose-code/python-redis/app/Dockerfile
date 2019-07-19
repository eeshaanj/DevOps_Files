# This Dockerfile will containarize the python app

FROM python:latest

ADD . /code

WORKDIR /code

RUN pip install -r requirements.txt

CMD ["python", "app.py"]
