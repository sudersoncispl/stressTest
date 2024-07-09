Need to install the loadtest globally, for the run the below command:
    sudo npm install -g loadtest

Then need to start the load test server, run the below command:
    testserver-loadtest --cores 2

Once the server started, now its ready to test any url, Example:
    loadtest google.com -t 20 -c 10

Basic syntax:
    loadtest [-n requests] [-c concurrency] [-k] URL