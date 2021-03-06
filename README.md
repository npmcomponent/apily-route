*This repository is a mirror of the [component](http://component.io) module [apily/route](http://github.com/apily/route). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/apily-route`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# route

Route component

## Installation

    $ component install apily/route

## API

### Route(String:path)

Create a route.

```js
var route = new Route('/users/:user_id');
```

### Route#create_regexp(String:path, [Array:keys])

Create the regexp that matches `path`.

```js
route.create_regexp('/users/:user_id');
```

### Route#match(String:path)

Test if `path` matches this route.

```js
route.match('/users/007');
```


## License

(The MIT License)

Copyright (c) 2013 Enrico Marino and Federico Spini

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
