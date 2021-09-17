# Building Images for VirtualBox

## Hypervisor

The image is built using Oracle VM VirtualBox hypervisor.

### Installing VirtualBox package

Oracle VirtualBox install instructions and packages are available at the [official page](https://www.virtualbox.org/wiki/Downloads).

## Building Images

### Validating

The build [prerequisites](../capi.md#prerequisites) for using `image-builder` for
building vbox images are managed by running:

```bash
cd image-builder/images/capi
make deps-vbox
```

### Generating a VirtualBox image

Only Windows 2019 images are available for VirtualBox hypervisor for now, to build local images
for development are made by running:

```bash
cd image-builder/images/capi
make build-node-vbox-local-windows-2019
```
