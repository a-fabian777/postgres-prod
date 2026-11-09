ARG POSTGRES_VERSION=17
FROM postgres:${POSTGRES_VERSION}-alpine
# instalar la extension o complemento de postgis
CMD ["postgres", "-c", "log_statement=all", "-c", "log_min_duration_statement=0"]
