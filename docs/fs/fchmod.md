# fs.fchmod(fd, mode, callback)

<!-- YAML
added: v0.4.7
changes:
  - version: v7.0.0
    pr-url: https://github.com/nodejs/node/pull/7897
    description: The `callback` parameter is no longer optional. Not passing
                 it will emit a deprecation warning.
-->

* `fd` {integer}
* `mode` {integer}
* `callback` {Function}

Asynchronous fchmod(2). No arguments other than a possible exception
are given to the completion callback.
