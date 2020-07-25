# Docker image with libindy and NodeJS

Base docker image with libindy, NodeJS, NPM and Yarn preinstalled. Also includes build tools needed to build indy-sdk for NodeJS.

https://hub.docker.com/r/animosolutions/indy-nodejs

## Usage

```lang=dockerfile
FROM animosolutions/indy-nodejs:latest
```

## Images

| tags                                                                         | libindy | NodeJS  | NPM    | Yarn   | OS           |
| ---------------------------------------------------------------------------- | ------- | ------- | ------ | ------ | ------------ |
| `animosolutions/indy-nodejs:latest`<br />`animosolutions/indy-nodejs:1.15.0` | 1.15.0  | 12.18.3 | 6.14.6 | 1.22.4 | Ubuntu 18.04 |

## Building

To build a docker image:

```sh
docker build -t animosolutions/indy-nodejs:latest -f indy-nodejs.dockerfile .
```
