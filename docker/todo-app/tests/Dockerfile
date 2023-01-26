FROM mjgargani/puppeteer:trybe1.0 AS todotests
COPY . .
EXPOSE 3000
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "test" ]