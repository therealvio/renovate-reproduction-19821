# renovate-reproduction-19821

## Current behaviour

`renovate` is able to detect `ops/Dockerfile`'s dependency: `public.ecr.aws/docker/library/node:18-alpine`.

## Expected behaviour

In [this repo](https://github.com/therealvio-org/ralphbot), `renovate` is _unable_ to detect the `ops/Dockerfile`'s dependency: `public.ecr.aws/docker/library/node:18-alpine`.
