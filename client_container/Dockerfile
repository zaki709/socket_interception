FROM alpine:latest

RUN apk add --no-cache gcc musl-dev
COPY client.c /client.c
RUN gcc -o client /client.c

CMD ["./client"]
