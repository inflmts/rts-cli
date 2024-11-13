# rts-cli

An unofficial [GNV RideRTS](https://riderts.app) CLI.

## Usage

Install from npm:

```sh
npm install -g @inflmts/rts-cli
```

See what commands are available:

```sh
rts
```

List routes:

```sh
rts routes
```

Get predictions:

```sh
rts predict <stop> # eg. 0473
```

See predictions in realtime:

```sh
rts board <stop>
```

Call the API yourself:

```sh
rts api <endpoint> [<params>...]

# examples:
rts api getroutes
rts api getstops rt=33 dir=OUTBOUND
```
