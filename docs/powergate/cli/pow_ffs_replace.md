## pow ffs replace

Pushes a CidConfig of c2 equal to c1, and removes c1

### Synopsis

Pushes a CidConfig of c2 equal to c1, and removes c1. This operation is more efficient than manually removing and adding in two separate operations

```
pow ffs replace [cid1] [cid2] [flags]
```

### Options

```
  -h, --help           help for replace
  -t, --token string   FFS access token
  -w, --watch          Watch the progress of the resulting job
```

### Options inherited from parent commands

```
      --config string          config file (default is $HOME/.powergate.yaml)
      --serverAddress string   address of the powergate service api (default "/ip4/127.0.0.1/tcp/5002")
```

### SEE ALSO

* [pow ffs](pow_ffs.md)	 - Provides commands to manage ffs

