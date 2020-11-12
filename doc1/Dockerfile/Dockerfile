FROM caddy:2.1.1-alpine

RUN mkdir '/user'

WORKDIR '/user'

RUN echo "Botylev Evgeny Aleksandrovitch" >> fullname.txt

COPY share /usr/share/caddy

COPY config/Caddyfile /etc/caddy/Caddyfile

VOLUME /usr/share/caddy
