# to run this file, use the command:
# docker build -t kjellpy .

# getting python version from official repo
FROM python:3.9

COPY app.py /
COPY requirements.txt /

WORKDIR /

RUN pip3 install -r requirements.txt

ENTRYPOINT python3 app.py