
# rucksack

 [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/rucksack.svg)](https://www.npmjs.com/package/rucksack) [![Downloads](https://img.shields.io/npm/dt/rucksack.svg)](https://www.npmjs.com/package/rucksack) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> JavaScript and CSS bundler.

## :cloud: Installation

```sh
$ npm i --save rucksack
```


## :clipboard: Example



```js
const Rucksack = require("rucksack");


let bundler = new Rucksack();

// Add remote url as resource
//bundler.add("https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.js");
bundler.add(`${__dirname}/data/main.js`);
bundler.add(`${__dirname}/data/another-main.js`);
bundler.bundle();
```

## :memo: Documentation


### `rucksack(a, b)`
JavaScript and CSS bundler.

#### Params
- **Number** `a`: Param descrpition.
- **Number** `b`: Param descrpition.

#### Return
- **Number** Return description.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
