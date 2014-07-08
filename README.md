inbox.js [![Build Status](https://travis-ci.org/inboxapp/inbox.js.svg?branch=master)](https://travis-ci.org/inboxapp/inbox.js)
========

Client-side SDK for communicating with the InboxApp API.

##Building Inbox.js

To begin with, it's necessary to set up a development environment:

```bash
git clone https://github.com/inboxapp/inbox.js.git

cd inbox.js

npm install

sudo npm install -g gulp karma-cli
```

Once a development environment is set up, you can build using the following command:

```bash
gulp build
```

Additionally, you can run tests with the following command:

```bash
gulp test
```

To run the examples web-server, begin by ensuring that you've set up [inbox](https://github.com/inboxapp/inbox) and have the API server up and running, then simply run the following command:

```bash
gulp serve --port=<OPTIONAL PORT> --host=<OPTIONAL HOST>
```

A more detailed guide on development, testing and contributing code is available in [CONTRIBUTING.md](CONTRIBUTING.md).
