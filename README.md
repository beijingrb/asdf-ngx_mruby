# asdf-ngx_mruby

[ngx_mruby](https://github.com/matsumotory/ngx_mruby) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```shell
asdf plugin-add ngx_mruby https://github.com/beijingrb/asdf-ngx_mruby
```

## Prerequisites

For Linux like Ubuntu you need these packages installed:

```bash
apt-get install make bison build-essential \
    openssh-server rake ruby2.0 ruby2.0-dev \
    libcurl4-openssl-dev libhiredis-dev libmarkdown2-dev \
    libcap-dev libcgroup-dev libpcre3 libpcre3-dev \
    libmysqlclient-dev
```

For macOS, you need use `homebrew` to install:

```bash
brew install openssl pcre
```

Note: lots of versions may not work on `macOS` due to some build options.

## Usage

List all available `ngx_mruby` versions:

```bash
asdf list-all ngx_mruby
```

Install one version of `ngx_mruby`:

```bash
asdf install ngx_mruby 1.20.1
```

Set a local version:

```bash
asdf local ngx_mruby 1.20.1
```

then `nginx` will be available in your shell path.

More `asdf` command details to [asdf](https://github.com/asdf-vm/asdf) README.

