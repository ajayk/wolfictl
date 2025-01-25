## wolfictl gh gc branch

Branch garbage collection commands used with GitHub

### Usage

```
wolfictl gh gc branch [flags]
```

### Synopsis

Branch garbage collection commands used with GitHub

Examples:

wolfictl gh gc branch https://github.com/wolfi-dev/os --match "wolfictl-"


### Options

```
      --all            close all branches if set
  -h, --help           help for branch
      --match string   pattern to match branches against
```

### Options inherited from parent commands

```
      --log-level string   log level (e.g. debug, info, warn, error) (default "WARN")
```

### SEE ALSO

* [wolfictl gh gc](wolfictl_gh_gc.md)	 - Garbage collection commands used with GitHub

