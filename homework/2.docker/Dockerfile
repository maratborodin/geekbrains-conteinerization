from python:3.9

COPY requirements.txt ./

RUN pip install -r requirements.txt

ADD . /app

EXPOSE 8080

RUN chmod +x /app/app.py

ENTRYPOINT /app/app.py runserver 0.0.0.0:8080 
