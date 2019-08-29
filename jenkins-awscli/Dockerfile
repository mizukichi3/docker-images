FROM jenkins:latest
USER root
RUN curl -kL https://bootstrap.pypa.io/get-pip.py | python
RUN pip install awscli
USER jenkins