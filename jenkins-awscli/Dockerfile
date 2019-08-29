FROM jenkins:latest
LABEL maintainer="mizukichi3 <https://github.com/mizukichi3>"
USER root
RUN curl -kL https://bootstrap.pypa.io/get-pip.py | python
RUN pip install awscli
USER jenkins