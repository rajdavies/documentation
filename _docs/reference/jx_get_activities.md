## jx get activities

Display one or many Activities on projects

### Synopsis

Display the current activities for one more more projects.

```
jx get activities [flags]
```

### Examples

```
  # List the current activities for all applications in the current team
  jx get activities
  
  # List the current activities for application 'foo'
  jx get act foo
```

### Options

```
  -b, --build string    The build number to filter on
  -f, --filter string   Text to filter the pipeline names
  -h, --help            help for activities
```

### SEE ALSO

* [jx get](jx_get.md)	 - Display one or many resources

###### Auto generated by spf13/cobra on 26-Feb-2018
