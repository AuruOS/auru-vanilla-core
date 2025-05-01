# auru-vanilla Image

Containerfile for building auru-base - unofficial Vanilla OS image.

This image is based on top of [`vanillaos/core`](https://github.com/Vanilla-OS/core-image/pkgs/container/core) and offers a basis for further images to be built without any included desktop of its own.
It is intended as an intermediary between upstream core and the downstream images of this Org, to allow any major build issues to be resolved in one place.

> [!CAUTION]
 This unofficall image of VanillaOS carefully install the image.This fork was created and is being developed by one developer, this project was made to: fix bugs in official releases, create a platform for creating the same images, create VanillaOS forks and also get verification from VanillaOS developers

> [!IMPORTANT]
 This image is in beta and this image is platform for new auru-vanilla based forks vanillaCore

## Build

```bash
vib build recipe.yml
podman image build -t AuruOS/auru-vanilla .
```
