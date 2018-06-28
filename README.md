# frontend-starter

Starter project for frontend learner or handy playground with [trans-loader](https://github.com/mizchi/trans-loader)

`trans-loader@0.1.1`

**Do not use it for production**

## How to develop

Run static server you love.

```
// node
$ npm install -g http-server
$ http-server -p 8000

// ruby
$ ruby -run -e httpd . -p 8000

// ptyhon3
$ python3 -m http.server 8000
```

and open http://localhost:8000

Edit your code and reload. Enjoy!

## Version with package.json

In default, trans-loader load latest version on npm.

you can indicate version with package.json's dependencies field.

```
{
  "dependencies": {
    "react": "16.4.1",
    "react-dom": "16.4.1"
  }
}
```