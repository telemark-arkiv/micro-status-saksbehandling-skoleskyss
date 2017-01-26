[![Build Status](https://travis-ci.org/telemark/micro-status-saksbehandling-skoleskyss.svg?branch=master)](https://travis-ci.org/telemark/micro-status-saksbehandling-skoleskyss)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

# micro-status-saksbehandling-skoleskyss
Stats for the Skoleskyss bot

## API

### **/raw**

Returns json of unformatted data.

#### GET

```bash
$ curl https://skoleskyss.saksbehandling.status.t-fk.win/raw
```

### **/json**

Returns json of formatted data.

#### GET

```bash
$ curl https://skoleskyss.saksbehandling.status.t-fk.win/json
```

### **/html**

Renders formatted data to html. 

#### GET

```bash
$ curl https://skoleskyss.saksbehandling.status.t-fk.win/html
```

## License

[MIT](LICENSE)

![alt text](https://robots.kebabstudios.party/micro-status-saksbehandling-skoleskyss.png "Robohash image of micro-status-saksbehandling-skoleskyss")
