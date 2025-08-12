# tupsulafi-site

Hugo SSG tupsula.fi version because Wordpress and PHP sucks. 

Site is currently running on beta.tupsula.fi. Site is powered by CF Pages.

## Building

Go to site's folder and run:

```bash
hugo
```

## Developing

Go to site's folder and run:

```bash
hugo server
```

## Install to your computer

Hugo needs go.

### Go

Install go from go.dev/doc/install

Or follow:

``` bash
wget https://go.dev/dl/go1.24.5.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.24.5.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go version
```

### Hugo

```bash
# Uses currently this version:
VERSION=0.148.2
wget https://github.com/gohugoio/hugo/releases/download/v${VERSION}/hugo_extended_${VERSION}_Linux-64bit.tar.gz
tar -xvzf hugo_extended_${VERSION}_Linux-64bit.tar.gz

# Installation location doesn't matter. Hugo is just a single bin file
sudo mv hugo /usr/local/bin/
sudo chmod +x /usr/local/bin/hugo
```

## Cloudflare Pages

Site is currently running on top of Cloudflare Pages. It is connected to this repository. Everytimes master branch gets pushed it builds a new site.

Custom domain can be created with CNAME record.

### Build configuration

- Build command: hugo
- Build output: public
- Root directory: tupsula

### Env variables

- HUGO_ENV = production
- HUGO_VERSION 0.148.2

## TODO

- Finish the site
- Change repo to public
