# APM Monitor

This library aims to help provision applications into our monitoring ecosystem.

### Usage

##### `package.json`

Add an entry for the `apm-monitor` under `dependencies` and run `npm install`.

```javascript
{
    ...
    "dependencies": {
        ...
        "apm-monitor": "gedigital-apm/apm-monitor"
    }
}
```

##### `app.js`

Import the `apm-monitor` library at the top of your entry-point file.

```javascript
require("apm-monitor");
...
```

### Configuration

Configuration options can be set via environment variables.

| Environment Variable | Default |     |
| ---                  | ---     | --- |
| `MONITORING_ENABLED` | `true`  | Set to `false` to disable application monitoring. |
| `MONITORING_DEBUG`   | `false` | Set to `true` to enable debug logs. |
