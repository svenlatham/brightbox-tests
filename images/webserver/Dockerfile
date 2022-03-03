# Based on https://raw.githubusercontent.com/docker-library/php/master/8.1/bullseye/apache/Dockerfile
FROM debian:bullseye-slim
RUN dd if=/dev/urandom of=rnd.bin bs=64M count=4 iflag=fullblock && echo ${UNIQID} >/tmpfile