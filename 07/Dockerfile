FROM nginx

RUN echo 120 > test.txt

RUN echo 120

RUN echo 120 > test.txt

COPY index.html /usr/share/nginx/html/index.html

ENV PASS=tajne_haslo

ENV db_host=server

COPY run.sh /run.sh

CMD bash /run.sh
