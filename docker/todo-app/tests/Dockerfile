FROM mjgargani/puppeteer:trybe1.0 AS todotests
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "test" ]