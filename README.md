# velveeva-cli
VELVEEVA command line tools for OSX and Linux.

# Requirements
* Native Linux/OSX [Docker](https://www.docker.com/products/docker) App
* (For OSX: [Homebrew](http://brew.sh/))

# Installation
## OSX
After installing Homebrew and Docker run
```
$ brew tap gacomm/tap && brew install velveeva-cli
```

To use VELVEEVA run `$ velveeva` from a terminal.

## Linux
After installing docker, clone this repo
```
$ git clone https://github.com/gacomm/velveeva-cli.git && cd velveeva-cli
```
Copy the `velveeva` script to somewhere in your path, like `/usr/local/bin`
```
$ sudo cp velveeva /usr/local/bin/velveeva
```

To use VELVEEVA run `$ sudo velveeva` from a terminal. (Sudo is required on Linux to start the Docker image velveeva-cli uses).
