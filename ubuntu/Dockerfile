FROM ubuntu:latest

RUN apt-get update && apt-get install -y --no-install-recommends wget build-essential libreadline-dev \ 
libncursesw5-dev libssl-dev libsqlite3-dev libgdbm-dev libbz2-dev liblzma-dev zlib1g-dev uuid-dev libffi-dev libdb-dev

RUN apt-get install -y vim less 

#任意バージョンのpython install
RUN apt -y install python3 python3-pip git

#必要なpythonパッケージをpipでインストール
RUN pip3 install --upgrade pip
RUN pip3 install --upgrade pip && pip install --no-cache-dir jupyterlab
RUN pip3 install --upgrade setuptools
