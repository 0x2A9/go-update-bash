# Bash script for updating Golang version

### Setup
- create a new file:
```
    sudo vim /usr/local/bin/go-update
```

- paste code from this repository `go-update` to the file, created in the previous step

- save the file and make it excecutable:
```
    sudo chmod +x /usr/local/bin/go-update
```
- the default tar archive is for **Linux AMD64**, it may be changed via an interactive menu (using commands without `-d` flag)

### Usage
- updating to the *latest* version with `-d` flag for the default `linux` OS and `amd64` architecture:
```
    sudo go-update latest -d
```
- updating to the *specific* version (both options are valid):
```
    sudo go-update 1.21.2 -d
```

```
    sudo go-update go1.21.2 -d
```
