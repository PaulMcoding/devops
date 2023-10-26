FROM python:latest
WORKDIR /Lab6
COPY . /Lab6
RUN apt update && apt-get upgrade -y && apt-get install -y
RUN make 
CMD ["./hello"]