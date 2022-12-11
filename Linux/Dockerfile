
FROM ubuntu


RUN apt-get update && apt-get install -y locales && rm -rf /var/lib/apt/lists/* \
	&& localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
RUN apt-get update && apt install -y --no-install-recommends samba samba-common-bin 
ENV LANG en_US.utf8


