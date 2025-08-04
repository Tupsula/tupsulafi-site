# tupsulafi-site

Hugo SSG tupsula.fi version because Wordpress and PHP sucks. 


## Using
Go to site's folder and run:
```
$ hugo server
```


## Installation

Hugo needs go. 

### Go
Install go via https://go.dev/doc/install

Or follow:
```
wget https://go.dev/dl/go1.24.5.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.24.5.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go version
```

### Hugo

```
# Uses currently this version:
VERSION=0.148.2
wget https://github.com/gohugoio/hugo/releases/download/v${VERSION}/hugo_extended_${VERSION}_Linux-64bit.tar.gz
tar -xvzf hugo_extended_${VERSION}_Linux-64bit.tar.gz

# Installation location doesn't matter. Hugo is just a single bin file
sudo mv hugo /usr/local/bin/
sudo chmod +x /usr/local/bin/hugo
```
