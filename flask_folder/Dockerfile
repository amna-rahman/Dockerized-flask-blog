

FROM ubuntu

RUN apt update

RUN apt install python3-pip -y



WORKDIR /app

COPY . .
RUN pip install -r requirements.txt
ENV FLASK_APP=flaskblog.py
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]




