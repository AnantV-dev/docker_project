FROM python:3
RUN mkdir /bata
WORKDIR /bata

COPY requirement.txt requirement.txt
RUN pip install -r requirement.txt

COPY . .
LABEL version = "1.0"

#CMD flask run --host=0.0.0.0 --port=5001
CMD ["./start.sh"]
