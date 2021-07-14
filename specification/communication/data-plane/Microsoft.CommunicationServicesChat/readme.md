# communicationservices

> see https://aka.ms/autorest

This is the AutoRest configuration file for communicationservices.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the communicationservices.

```yaml
openapi-type: data-plane
tag: package-2020-07-20-preview1
```

### Tag: package-2020-09-21-preview2

These settings apply only when `--tag=package-2020-09-21-preview2` is specified on the command line.

```yaml $(tag) == 'package-2020-09-21-preview2'
input-file:
  - preview/2020-09-21-preview2/communicationserviceschat.json
title:
  Azure Communication Services
```

### Tag: package-2020-11-01-preview3

These settings apply only when `--tag=package-2020-11-01-preview3` is specified on the command line.

```yaml $(tag) == 'package-2020-11-01-preview3'
input-file:
  - preview/2020-11-01-preview3/communicationserviceschat.json
title:
  Azure Communication Services
```

### Tag: package-2021-01-27-preview4

These settings apply only when `--tag=package-2021-01-27-preview4` is specified on the command line.

```yaml $(tag) == 'package-2021-01-27-preview4'
input-file:
  - preview/2021-01-27-preview4/communicationserviceschat.json
title:
  Azure Communication Services
```

### Tag: package-2021-03-01-preview5

These settings apply only when `--tag=package-2021-03-01-preview5` is specified on the command line.

```yaml $(tag) == 'package-2021-03-01-preview5'
input-file:
  - preview/2021-03-01-preview5/communicationserviceschat.json
title:
  Azure Communication Services
```

### Tag: package-chat-2021-03-07

These settings apply only when `--tag=package-chat-2021-03-07` is specified on the command line.

```yaml $(tag) == 'package-chat-2021-03-07'
input-file:
  - stable/2021-03-07/communicationserviceschat.json
title:
  Azure Communication Services
```

### Tag: package-chat-2021-04-05-preview6

These settings apply only when `--tag=package-2021-04-05-preview6` is specified on the command line.

```yaml $(tag) == 'package-chat-2021-04-05-preview6'
input-file:
  - preview/2021-04-05-preview6/communicationserviceschat.json
title:
  Azure Communication Services
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

## Python

See configuration in [readme.python.md](./readme.python.md)

## Ruby

See configuration in [readme.ruby.md](./readme.ruby.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)