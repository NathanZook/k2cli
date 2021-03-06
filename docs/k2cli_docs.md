## k2cli docs

Generate markdown docs

### Synopsis


Generate complete markdown doc tree for k2cli

```
k2cli docs [output dir]
```

### Options inherited from parent commands

```
  -d, --docker-host string   docker host address (default "unix:///var/run/docker.sock")
  -i, --image string         k2 container image (default "quay.io/samsung_cnct/k2:latest")
  -k, --k2config string      config file for k2cli (default "/Users/marat/.k2cli.yaml)"
  -v, --keep-alive           keep stopped containers.
  -w, --log-path string      Save output output of container action to path
  -x, --log-success          Display full action logs on success
  -o, --output string        k2 output folder (default "/Users/marat/.kraken")
  -t, --timeout int          timeout (in seconds) for container actions (default 1200)
```

### SEE ALSO
* [k2cli](k2cli.md)	 - CLI for k2 Kubernetes cluster provisioner

###### Auto generated by spf13/cobra on 16-Nov-2016
