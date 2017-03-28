# velveeva-cli
💻 [VELVEEVA](http://www.github.com/drewsynan/velveeva) command line tools for OSX and Linux.

![screenshot](https://raw.githubusercontent.com/drewsynan/velveeva-cli/master/ss.png)

# Requirements
* Native Linux/OSX [Docker](https://www.docker.com/products/docker) App
* (For OSX: [Homebrew](http://brew.sh/))

# Installation
##  OSX
After installing Homebrew and Docker run
```
$ brew tap drewsynan/velveeva && brew install velveeva-cli
```

To use VELVEEVA run `$ velveeva` from a terminal.

Use `$ velveeva init` to create a new project, and `$ velveeva help` for more info on available commands.

## 🐧 Linux
After installing docker, clone this repo
```
$ git clone https://github.com/drewsynan/velveeva-cli.git && cd velveeva-cli
```
Copy the `velveeva` script to somewhere in your path, like `/usr/local/bin`
```
$ sudo cp velveeva /usr/local/bin/velveeva
```

To use VELVEEVA run `$ sudo velveeva` from a terminal. (`sudo` is required on Linux to start the Docker container `velveeva-cli` uses internally).

Use `$ sudo velveeva init` to create a new project, and `$ sudo velveeva help` for more info on available commands.

# Updating the utility image
To update the internal utility image velveeva-cli uses to the latest version of VELVEEVA run `$ velveeva update` (OSX) or `$ sudo velveeva update` (Linux)
