FROM golang:1.16

WORKDIR /usr/src/app

COPY . .

RUN go build -o server

ENV PORT=8080
ENV REQUEST_ORIGIN=https://example.com
ENV REDIS_HOST=
ENV POSTGRES_HOST=
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_DATABASE=postgres

EXPOSE $PORT

CMD ["./server"]
