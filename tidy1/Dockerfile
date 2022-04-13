FROM ubuntu:21.10

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update
RUN apt install -y r-base
RUN Rscript -e "install.packages('tibble')"

CMD ["R"]
