#hackingdays.com

[![Build Status](https://travis-ci.org/hackingdays/hackingdays.com.svg?branch=master)](https://travis-ci.org/hackingdays/hackingdays.com)
[![Dependencies Status](https://david-dm.org/hackingdays/hackingdays.com.svg)](https://github.com/hackingdays/hackingdays.com)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/hackingdays/hackingdays.com/raw/master/LICENSE)
[![Paypal Donate](https://img.shields.io/badge/paypal-donate-blue.svg)](https://www.paypal.me/phatpham9)
[![Fork](https://img.shields.io/github/forks/hackingdays/hackingdays.com.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/hackingdays/hackingdays.com#fork-destination-box)

Hacking Days community - Everyday is a hacking day.

### Installation

Install meteor

```
curl https://install.meteor.com | /bin/sh
```

### Running

#### Development

Start app

```
npm start
```

#### Production

Build app

```
npm run build
```

Set env variables & Start app

```
export BIND_IP=127.0.0.1
export PORT=9000
export MONGO_URL=mongodb://127.0.0.1/hackingdays
export ROOT_URL=http://hackingdays.com
node bundle/main.js
```

### References

* [Roadmap](https://trello.com/b/MgcW7j2h/hackingdays-com)