## Environment

- Python 3.6.0
- Flask 0.12.2

## Setup

- clone this repository

```
$ git clone https://github.com/kenzo0107/toda-tocochan-bus-on-ibmbluemix
$ cd toda-tocochan-bus-on-ibmbluemix
```

- Install cloud foundry command

```
$ brew tap cloudfoundry/tap
$ brew install cf-cli
```

## Deploy

```
$ cf api https://api.ng.bluemix.net
$ cf login
$ cf push <application name>
```
