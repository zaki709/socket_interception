FROM alpine:latest

RUN apk add --no-cache gcc musl-dev
COPY server.c /server.c
RUN gcc -o server /server.c

CMD ["./server"]
