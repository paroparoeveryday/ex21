FROM python:3.9-slim

#作業ディレクトリを変更
WORKDIR /tmp/mydir

#ファイルのコピー
COPY requirements.txt ${PWD}

#pythonのパッケージをインストール
RUN pip install -r requirements.txt
