# Winston console formatter

It's look's like yaml \o/

This is custom config for default winston console transform.

```
  npm install winston-console-formatter
```

``` js
  var yamlFormatter = require('winston-console-formatter')
  new (winston.transform.Console)(yamlFormatter.config())
```

