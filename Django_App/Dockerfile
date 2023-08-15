FROM python:3.9
WORKDIR /python_app
COPY . /python_app
RUN pip install -r requirements.txt
EXPOSE 8002
CMD [ "python","manage.py","runserver","0.0.0.0:8002" ]