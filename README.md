# djp-mailcatcher

A [ddb](https://inetum-orleans.github.io/docker-devbox-ddb) jsonnet package (**djp**).

## Description

Mailcatcher **djp** package.

## Snippet

- `ddb.yml`

```yaml
cookiecutter:
  templates:
    - template: gh:inetum-orleans/djp-mailcatcher
```

- `docker-compose.yml.jsonnet`

```jsonnet
ddb.Compose(
  ddb.with(import '.docker/mailcatcher/djp.libjsonnet')
)
```

## Parameters

| name  | type | description |
| ------------- | ------------- | ------------- |
| domain  | string<br>`{service}.{core.domain.value}`  | Domain name

## Usage

Please check [jsonnet feature](https://inetum-orleans.github.io/docker-devbox-ddb/features/jsonnet/#ddb-jsonnet-packages-djp)
to understand how to include a **djp** package inside a [ddb](https://inetum-orleans.github.io/docker-devbox-ddb) project.

Looking for other [djp packages](https://github.com/inetum-orleans?q=djp-) ? Check github repositories starting with `djp-`.
