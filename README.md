# libyaml

Defines the YAML specification for the Native Scheduler. Additional documentation can be found [here](https://help.replicated.com/docs/native/packaging-an-application/overview/).

The top level keys/sections can be found in [root_config.go](root_config.go). From there the rest of the structure is defined in the appropriately named files.

## Build docker container

```bash
make docker
```

## Run docker container

```bash
make shell
```

## Install dependencies

```bash
make deps
```

## Run unit tests

```bash
make test
```
