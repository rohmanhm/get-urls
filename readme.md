# get-urls-to-array

> Get all URLs in a string

The URLs will be [normalized](https://github.com/sindresorhus/normalize-url).


## Install

```
$ npm install --save get-urls-to-array
```


## Usage

```js
const text = 'Lorem ipsum dolor sit amet, //sindresorhus.com consectetuer adipiscing http://yeoman.io elit.';

getUrlsToArray(text);
//=> ['http://sindresorhus.com', 'http://yeoman.io']
```


## API

### getUrlsToArray(text, [options])

Returns a `Array<string>` of URLs.

### text

Type: `string`

### options

Type: `Object`

See the `normalize-url` [options](https://github.com/sindresorhus/normalize-url#options).


## Related

- [get-urls-cli](https://github.com/sindresorhus/get-urls-cli) - CLI for this module
- [linkify-urls](https://github.com/sindresorhus/linkify-urls) - Linkify URLs in text
- [url-regex](https://github.com/kevva/url-regex) - Regular expression for matching URLs


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
MIT © [Roman Masyhar](https://github.com/rohmanhm)
