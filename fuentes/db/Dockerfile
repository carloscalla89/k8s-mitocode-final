FROM mysql:5.7.8

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=petclinic
ENV MYSQL_ROOT_HOST=%

COPY ./scripts/ /docker-entrypoint-initdb.d/
CMD ["--default-authentication-plugin=mysql_native_password"]