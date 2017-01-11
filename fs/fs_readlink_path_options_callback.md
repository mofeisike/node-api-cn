<!-- YAML
added: v0.1.31
-->

* `path` {String | Buffer}
* `options` {String | Object}
  * `encoding` {String} default = `'utf8'`
* `callback` {Function}

Asynchronous readlink(2). The callback gets two arguments `(err,
linkString)`.

The optional `options` argument can be a string specifying an encoding, or an
object with an `encoding` property specifying the character encoding to use for
the link path passed to the callback. If the `encoding` is set to `'buffer'`,
the link path returned will be passed as a `Buffer` object.
