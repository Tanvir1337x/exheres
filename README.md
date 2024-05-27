# About

Personal Exheres for Exherbo Linux based systems.

## Note

Currently, it's a boilerplate repository.

## Using This Repository

Edit `/etc/paludis/repositories/tanvir.conf` and include the following:

```r
format = e
location = /var/db/paludis/repositories/tanvir
sync = git+https://github.com/TanvirOnGH/exheres.git
sync_options = --branch=dev
```

Then run `cave sync tanvir`.
