## jx get

Display one or many resources

### Synopsis

Display one or many resources. 

Valid resource types include: 

  * environments (aka 'env')  
  * pipelines (aka 'pipe')  
  * urls (aka 'url')

```
jx get TYPE [flags]
```

### Examples

```
  # List all pipeines
  jx get pipeline
  
  # List all URLs for services in the current namespace
  jx get url
```

### Options

```
  -h, --help   help for get
```

### SEE ALSO

* [jx](jx.md)	 - jx is a command line tool for working with Jenkins X
* [jx get activities](jx_get_activities.md)	 - Display one or many Activities on projects
* [jx get addons](jx_get_addons.md)	 - Lists the addons
* [jx get apps](jx_get_apps.md)	 - Display one or many Applications and their versions
* [jx get build](jx_get_build.md)	 - Display one or many build resources
* [jx get environments](jx_get_environments.md)	 - Display one or many Environments
* [jx get git](jx_get_git.md)	 - Display the current registered git service URLs
* [jx get pipelines](jx_get_pipelines.md)	 - Display one or many Pipelines
* [jx get urls](jx_get_urls.md)	 - Display one or many URLs

###### Auto generated by spf13/cobra on 26-Feb-2018
