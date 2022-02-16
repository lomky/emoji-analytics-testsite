FROM debian

RUN apt update
RUN apt install -y hugo

COPY . /srv/hugo

WORKDIR /srv/hugo

CMD hugo server -D --bind 0.0.0.0
