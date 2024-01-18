FROM fedora
RUN dnf -yqq install nginx
RUN dnf -yqq install python3
COPY app.py
EXPOSE 5000
ENTRYPOINT python3 app.py
