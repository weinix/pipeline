FROM gcr.io/google.com/cloudsdktool/cloud-sdk:latest

# Install golang
RUN curl https://dl.google.com/go/go1.14.linux-amd64.tar.gz > go1.14.tar.gz
RUN tar -C /usr/local -xzf go1.14.tar.gz
ENV PATH="${PATH}:/usr/local/go/bin"

# Install ko
ENV GOBIN=/usr/local/go/bin
RUN go get github.com/google/ko/cmd/ko
