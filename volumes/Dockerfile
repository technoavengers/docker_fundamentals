FROM busybox
RUN mkdir /myvolume
RUN echo "hello to data volumes" >> /myvolume/hello.txt
VOLUME /myvolume
CMD ["sh"]