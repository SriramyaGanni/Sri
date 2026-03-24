FROM ubuntu:22.04
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    apt-get clean
COPY ./app /app
WORKDIR /app
EXPOSE 80
CMD ["python3", "-m", "http.server", "80"]
