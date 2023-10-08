# Bash script for Golang version updating

### Setup
- create a new file:
```
    sudo vim /usr/local/bin/go-update
```

- paste code from the `go-update` to the file, opened with the `vim`
- the default tar archive is for Linux AMD64, it may be changed

- save the file and make it excecutable:
```
    sudo chmod +x /usr/local/bin/go-update
```

### Usage
- update to the *latest* version:
```
    sudo go-update latest
```
- update to the *specific* version (both options are valid):
```
    sudo go-update 1.21.2
```

```
    sudo go-update go1.21.2
```
