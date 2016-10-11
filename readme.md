# vhp 1.0.0

Utility classes for vh percentages

#### Stats

121 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev vhp
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/vhp
```

ssh:
```
git clone git@github.com:tachyons-css/vhp.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "vhp";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/vhp@1.0.0/css/vhp.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/vhp">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
.vhp-1 { height: 1vh; }
.vhp-10 { height: 10vh; }
.vhp-20 { height: 20vh; }
.vhp-25 { height: 25vh; }
.vhp-30 { height: 30vh; }
.vhp-33 { height: 33vh; }
.vhp-34 { height: 34vh; }
.vhp-40 { height: 40vh; }
.vhp-50 { height: 50vh; }
.vhp-60 { height: 60vh; }
.vhp-67 { height: 67vh; }
.vhp-70 { height: 70vh; }
.vhp-75 { height: 75vh; }
.vhp-80 { height: 80vh; }
.vhp-90 { height: 90vh; }
.vhp-99 { height: 99vh; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

