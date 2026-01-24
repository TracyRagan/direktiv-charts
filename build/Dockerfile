FROM golang:1.26rc2

COPY . /myapp

RUN cd /myapp && go build -o /app main.go
RUN mkdir /tmp/crds && mkdir /tmp/templates

ENTRYPOINT ["/app"]
