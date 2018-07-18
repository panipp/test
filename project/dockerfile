FROM python:3.6

RUN mkdir /web_container
WORKDIR /web_container
ADD ./requirement.txt /web_container/requirement.txt
RUN pip install -r requirement.txt
ADD . /web_container