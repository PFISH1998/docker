FROM python:3.6
ADD . /code
WORKDIR /code
EXPOSE 6800
RUN pip3 install -r requirements.txt
COPY ./scrapyd.conf /etc/scrapyd/
CMD scrapyd