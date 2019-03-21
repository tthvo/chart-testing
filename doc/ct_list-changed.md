## ct list-changed

List changed charts

### Synopsis

"List changed charts based on configured charts directories,
"remote, and target branch

```
ct list-changed [flags]
```

### Options

```
      --chart-dirs strings        Directories containing Helm charts. May be specified multiple times
                                  or separate values with commas (default [charts])
      --config string             Config file
      --excluded-charts strings   Charts that should be skipped. May be specified multiple times
                                  or separate values with commas
  -h, --help                      help for list-changed
      --remote string             The name of the Git remote used to identify changed charts (default "origin")
      --target-branch string      The name of the target branch used to identify changed charts (default "master")
```

### SEE ALSO

* [ct](ct.md)	 - The Helm chart testing tool

###### Auto generated by spf13/cobra on 26-Feb-2019