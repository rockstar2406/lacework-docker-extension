## Installing the Lacework Docker extension

`docker extension install mennov/lacework-docker-extension:v0.1.1`

or, if the extension is already installed, you can easily upgrade with

`docker extension update mennov/lacework-docker-extension:v0.1.1`

## Build

To enable Honeycomb event logging, ensure the following are build arguments for the docker build.
- `HONEYCOMB_TEAM` api key for sending data to honeycomb
- `HONEYCOMB_DATASET` dataset for honeycomb

