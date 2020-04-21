FROM python:3-buster

# Place app in container.
COPY . /opt/www
WORKDIR /opt/www

# Install dependencies.
RUN pip install -r requirements.txt

EXPOSE ${EXPOSE_PORT}
CMD python index.py