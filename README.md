# k6-performance-test-websocket
Example of performance test for websocket with k6

## How run the tests:

- Clone this repo:
https://github.com/loadimpact/k6

- Install the dependencies:
```console
npm install
```

- Create your scripts for test.

- Run in the command line your script (example):
```console
docker-compose run -v D:/user/k6/scripts:/scripts k6 run scripts/ws.js --vus 300 --duration 60s
```

### If you need documentation of k6: https://docs.k6.io/docs
