FROM python:3.6
WORKDIR /code
ADD requirements.txt /code
RUN pip3 install -r requirements.txt
EXPOSE 8000
# docker run -it -v /root/code/gerapy:/code  --privileged=true -p 8000:8000 gerapy
CMD gerapy runserver 0.0.0.0:8000