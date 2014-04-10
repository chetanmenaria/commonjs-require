# Common.js require definition

Simple common.js `require()` definition.

## Usage

Include on top of your file and register modules with `require.register(name, fn)`

## API

* `require(name)` — loads registered module and returns its `exports`.
* `require.register(name, fn)` — registers new module. `fn` should have signature `exports, require, module`.
* `require.list()` — lists all registered modules.
* `require.clearCache(name)` — allows to clear the require cache. You can pass the optional parameter `name` to clear the cache of a specific module.

## License

MIT

Copyright (c) 2013 Paul Miller (http://paulmillr.com/)
