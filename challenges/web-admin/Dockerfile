FROM python:3.5

MAINTAINER David Wyde (david.wyde@gmail.com)

RUN pip3 install tornado

RUN useradd -m challenge

COPY challenge.py flag /home/challenge/

EXPOSE 8888

USER challenge

WORKDIR /home/challenge

CMD ["python3", "challenge.py"]
