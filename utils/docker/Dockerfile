FROM ubuntu:utopic

RUN apt-get update
RUN apt-get -y install git asciidoc po4a libunicode-linebreak-perl dblatex gettext make pandoc texlive-lang-*

ADD ./make.docker.sh /opt/make.docker.sh
