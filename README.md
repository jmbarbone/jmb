# jmb

Jordan's Main Bin

This repo contains scripts that make Jordan's (me) life a little easier.

To start, set your the current working directory to this repo, then:

``` bash
bash ./configure
```

Respond to any prompts and have fun.

## Examples


### pak

Update **R** packages with [`{pak}`](https://github.com/r-lib/pak)

```sh
pak mark
```

### pak-install

Installs [`{pak}`](https://github.com/r-lib/pak).
Either the CRAN release or a developmental version.

```sh
pak-install
```

### update-r-pkgs

Tries to update _old_ R packages using [`{pak}`](https://github.com/r-lib/pak).

```sh
update-r-pkgs
```

### git-checkout

Checkout git branch with pattern match.

``` sh
git-checkout 11
```

```
Matched branches:
  11-bug-fix
```

