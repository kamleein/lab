FROM ubuntu:26.04
RUN apt-get update && apt install -y curl ca-certificates && curl https://example.com
WORKDIR /app
COPY greet .
CMD ["./greet"]
