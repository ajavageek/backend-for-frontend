FROM python:3.10-alpine

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY app.py .

EXPOSE 5001

CMD [ "python3", "-m" , "flask", "run", "--port=5001", "--host=0.0.0.0"]
