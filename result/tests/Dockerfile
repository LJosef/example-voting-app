FROM index.alauda.cn/library/node:5.1-slim
RUN npm install -g phantomjs
ADD . /app
WORKDIR /app
CMD ["/app/test_result.sh"]
