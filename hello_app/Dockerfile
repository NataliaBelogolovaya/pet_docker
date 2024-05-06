FROM python:3.13.0a6-alpine3.19
MAINTAINER Natalia_Myslivets
RUN pip install -U Flask
RUN mkdir /app
COPY hello_app /app
WORKDIR /app
ENTRYPOINT [«python»]
CMD [«hello.py»]