# About

Personal [Exheres](https://www.exherbolinux.org/docs/eapi/exheres-for-smarties.html) repository for [Exherbo](https://www.exherbolinux.org) Linux based systems.

> [!NOTE]  
> Currently, it's a boilerplate repository.

## Using This Repository

Edit `/etc/paludis/repositories/tanvir.conf` and include the following:

```r
format = e
location = /var/db/paludis/repositories/tanvir
sync = git+https://github.com/TanvirOnGH/exheres.git
sync_options = --branch=dev
```

Then run `cave sync tanvir`.

## References

- [Exherbo Linux](https://www.exherbolinux.org)
- [Paludis](https://paludis.exherbolinux.org)
- [Exheres for Smarties](https://www.exherbolinux.org/docs/eapi/exheres-for-smarties.html)
- [Exherbo Gitlab Groups](https://gitlab.exherbo.org/explore/groups)
