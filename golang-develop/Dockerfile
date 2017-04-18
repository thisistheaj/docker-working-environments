FROM golang
RUN apt-get -y update
RUN apt-get install -y vim
RUN apt-get install -y curl
#RUN apt-get install -y git
#RUN apt-get install -y golang

#ENV GOPATH /usr/local/go
#ENV PATH $PATH:/usr/local/go/bin

RUN go get -u github.com/revel/cmd/revel
RUN curl https://glide.sh/get | sh

CMD bash
