{%- if cookiecutter.store == "mysql" -%}
FROM mysql:5.6.40
{%- elif cookiecutter.store == "mariadb" -%}
FROM mariadb:5.5.60
{%- elif cookiecutter.store == "postgres" -%}
FROM postgres:10.4-alpine
{%- else -%}
FROM mongodb:3.2.20-jessie
{%- endif -%}
