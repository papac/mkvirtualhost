# mkvirtualhost

Create your apache virtual host

# Usage

## Install

Install of the mkvirtualhost is very easiest

```bash
$ git clone https://github.com/papac/mkvirtualhost.git --depth=1
$ cd mkvirtualhost
$ sudo cp virtual /usr/local/bin/mkvirtaulhost
$ mkvirtualhost help
```

## Add virtualhost

Add virtual host

```bash
$ sudo mkvirtualhost add /path/to/your/documentroot domaine_name [option]
```

option

+ `--with-git` option is enabled, mkvirtualhost initialize git in your project
+ `--with-local-log` option is enabled, mkvirtualhost add the apache logs in your project

## Remove virtualhost

Remove virtual host

```bash
$ sudo mkvirtualhost remove domaine_name
```
## list virtualhost

List your enable virtual host

```bash
$ sudo mkvirtualhost list
```

## has

Test if virtual host exist

```bash
$ sudo mkvirtaulhost has domain.dev
```

### LICENSE

MIT

