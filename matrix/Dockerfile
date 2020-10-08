FROM scratch
LABEL maintainer="patrik"
LABEL description="This is description for matrix image."
ADD alpine-minirootfs-3.12.0-x86_64.tar.gz /
RUN apk add cmatrix
CMD [ "cmatrix" ]
