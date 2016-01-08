# Binary Test Applications

A collection of applications used for testing the binary buildpack

## Applications

| Name | Description
| ---- | -----------
| `binary-go-application` | Go application without dependencies

### Output Content

All applications support the following REST operations:

| URI | Description
| --- | -----------
| `GET /` | The health of the application

## Deploying to Cloud Foundry

Each test application contains a `manifest.yml` file which allows the built application to be deployed to Cloud Foundry by simply issuing:

```
cf push
```
