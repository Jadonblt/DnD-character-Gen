FROM python:3.7

WORKDIR /app

COPY . . 

RUN pip install -r requirements.txt

ENV MYSQL_USER "root"
ENV MYSQL_PWD "rootpassword"
ENV MYSQL_IP "0.0.0.0:3306"
ENV MYSQL_DB "db"
ENV MYSQL_SK "45ytdhtryt6y"

EXPOSE 5000

ENTRYPOINT [ "python", "app.py" ]