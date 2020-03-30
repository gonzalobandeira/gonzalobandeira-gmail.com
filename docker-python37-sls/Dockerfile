FROM docker:19.03.0
# Image with Python 3.7.1, Docker and Serverless
RUN apk update && apk upgrade && apk add bash git py3-setuptools
RUN alias python=python3
RUN apk add py3-pip
RUN pip3 install pipenv
RUN apk add --upgrade npm
RUN npm config set prefix /usr/local
RUN npm install -g serverless
