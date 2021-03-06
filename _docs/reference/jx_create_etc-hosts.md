## jx create etc-hosts

Creates a new git server URL

### Synopsis

Creates /etc/hosts entries for all current exposed services

```
jx create etc-hosts kind [url] [flags]
```

### Examples

```
  # Creates /etc/hosts entries for all current exposed services
  sudo jx create etc-hosts
```

### Options

```
  -h, --help          help for etc-hosts
  -i, --ip string     The IP address of the node to point the host entries to
  -n, --name string   The etc hosts file to edit (default "/etc/hosts")
```

### SEE ALSO

* [jx create](jx_create.md)	 - Create a new resource

###### Auto generated by spf13/cobra on 26-Feb-2018
