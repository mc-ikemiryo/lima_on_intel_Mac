# lima with docker on intel Mac with virtiofs

# usage


## 1. install lima

https://github.com/lima-vm/lima

## 2. start lima

```
$ limactl start sample
INFO[0000] Creating an instance "sample" from template://default (Not from template://sample)
WARN[0000] This form is deprecated. Use `limactl start --name=sample template://default` instead
? Creating an instance "sample"  [Use arrows to move, type to filter]
  Proceed with the current configuration
> Open an editor to review or modify the current configuration
  Choose another example (docker, podman, archlinux, fedora, ...)
  Exit
```

### Replace the contents with [lima.yaml](https://github.com/mc-ikemiryo/lima_on_intel_Mac/blob/main/lima.yaml)
