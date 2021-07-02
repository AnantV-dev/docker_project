FROM python:3
RUN mkdir /ui
WORKDIR /ui

COPY requirement.txt requirement.txt
RUN pip install -r requirement.txt

COPY . .
LABEL version = "1.0"

CMD ["./start.sh"]
#CMD flask run --host=0.0.0.0 --port=5004
