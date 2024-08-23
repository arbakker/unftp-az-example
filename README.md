# README

Example docker-compose [unftp](https://github.com/bolcom/unFTP) deployment of unFTP with Azurite (az blob storage emulator).

Requires unFTP Docker image build from https://github.com/bolcom/unFTP/commit/83696d180ec94e6bf37875de75af811037bf6bbf.

Run with:

```sh
docker-compose up
```

Then connect to unFTP with:

```sh
lftp
> connect ftp://localhost:2121
```
