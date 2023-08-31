FROM debian

RUN apt-get update && apt-get install -y \
    curl \
    golang

COPY source_code/ ./app

WORKDIR /app

RUN go get github.com/redis/go-redis/v9

RUN go build -o app

CMD ["./app"]
