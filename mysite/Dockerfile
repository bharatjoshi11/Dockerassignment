FROM python:3.11.1-alpine3.15
WORKDIR /mysite
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . /mysite
EXPOSE 8000
CMD [ "python","manage.py","runserver","0.0.0.0:8000" ]
