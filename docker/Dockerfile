FROM amazon/aws-cli:2.0.6

# python package
RUN pip install --upgrade pip
RUN pip install aws-sam-cli

# コンテナログイン時のディレクトリ指定
WORKDIR /work/

CMD ["/bin/bash"]