# hashicorp-installer
A short POSIX compliant shell script to install hashicorp packages

## Install Requirements
You need to have following tools in place:
* awk
* jq
* curl
* unzip

Awk, Curl and Unzip should be already installed on MacOS and Debian/Ubuntu.

### Debian / Ubuntu
```sh
$ apt install jq
```

### MacOS
```sh
brew install jq
```

## Use Installer

```sh
$ ./hashicorp-installer.sh terraform

$ ./hashicorp-installer.sh packer
```
