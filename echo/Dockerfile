#
# A very minimal Echo container
#

FROM my/scratch
MAINTAINER Akash Shende <akash@anoosmar.com>

COPY libc.so.6 '/lib/x86_64-linux-gnu/libc.so.6'
COPY ld-linux-x86-64.so.2 '/lib64/ld-linux-x86-64.so.2'
COPY echo /bin/echo

ENTRYPOINT /bin/echo
CMD [""]
