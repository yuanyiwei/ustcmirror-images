FROM ustcmirror/base:debian
LABEL maintainer="Keyu Tao <taoky@ustclug.org>"
RUN apt update && apt install -y yum-utils createrepo python3 python3-requests
ADD tunasync /usr/local/lib/tunasync
ADD sync.sh /
