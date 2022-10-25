FROM python:3.11.0-slim-bullseye@sha256:7de7f8d769f5a99b77f8d3e27b2b581301545c36655d3bbb84d6fd0c300496a1

ADD requirements.txt /tmp/flask-requirements.txt
RUN pip3 install -qr /tmp/flask-requirements.txt
RUN mkdir /code

ENTRYPOINT ["python3", "/code/service.py"]
