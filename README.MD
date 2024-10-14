Need to install loadtest globally, run following command to install loadtest globally.
    sudo npm install -g loadtest

Then need to start the load test server, run the below command:
    testserver-loadtest --cores 2

Once the server started, now its ready to test any url, Example:
    loadtest https://google.com -t 20 -c 10

Basic syntax:
    loadtest [-n requests] [-c concurrency] [-k] URL

For complete reference visit: https://www.npmjs.com/package/loadtest