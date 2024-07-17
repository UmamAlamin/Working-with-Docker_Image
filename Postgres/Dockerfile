FROM postgres:16.2

ENV POSTGRES_USER=user 
ENV POSTGRES_PASSWORD=qwerty124
ENV POSTGRES_DB=pg-db


COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432

#docker build -t <nama image><dir docker file>
#running container -----> docker run -d -p<port host>:<port container>--name<nama container><nama image>
