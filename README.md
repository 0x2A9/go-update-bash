# Go Update Bash
Bash script for updating **Golang** version

# Set Up
- Create a new file:
	```bash
	sudo vim /usr/local/bin/go-update
	```

- Paste code from this repository `go-update` to the file, created in the previous step

- Save the file and make it excecutable:
	```bash
	sudo chmod +x /usr/local/bin/go-update
	```
- The default tar archive is for **Linux AMD64**, it may be changed via an interactive menu (using commands without `-d` flag)

# Usage
- Updating to the *latest* version with `-d` flag for the default `linux` OS and `amd64` architecture:
	```bash
	sudo go-update latest -d
	```
- Updating to the *specific* version (both options are valid):
	```bash
	sudo go-update 1.21.2 -d
	```

	```bash
	sudo go-update go1.21.2 -d
	```
