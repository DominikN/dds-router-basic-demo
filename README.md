# dds-router-basic-demo

A simple demo with a DDS router

## Quick start

### Localhost

To run the full talker-listener demo on one localhost:

```bash
cd localhost
docker compose up --build
```

### Husarnet (but on the same host)

To run the full talker-listener demo over Husarnet (but on one localhost):

```bash
cd husarnet
export MY_HUSARNET_JOINCODE=fc94:b01d:1803:8dd8:b293:5c7d:7639:932a/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx # place you join code here
echo "JOINCODE=${MY_HUSARNET_JOINCODE}" > .env
docker compose up --build
```