FROM fedora:35

RUN dnf install -y xclock
    
WORKDIR /usr/app
COPY ./myscript.sh /usr/app

ENV MYENV=otc

CMD ["/usr/app/myscript.sh"]

