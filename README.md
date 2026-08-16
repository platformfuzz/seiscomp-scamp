# seiscomp-scamp

![CI](https://github.com/platformfuzz/seiscomp-scamp/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scamp/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scamp image built with public gsm. Not gempa-supported.

The process computes amplitudes.

**Package:** [ghcr.io/platformfuzz/seiscomp-scamp](https://github.com/platformfuzz/seiscomp-scamp/pkgs/container/seiscomp-scamp)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scamp:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scamp:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scamp:test .
docker run --rm seiscomp-scamp:test
```
