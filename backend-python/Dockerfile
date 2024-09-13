FROM python:3.8.20-alpine

WORKDIR /app

RUN pip install flask pymongo && \
    chmod 0500 /tmp

COPY ./src/app.py /app/app.py

CMD [ "/usr/local/bin/python", "app.py"]
