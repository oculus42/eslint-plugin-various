# eslint-plugin-jquery

Disallow jQuery functions with native equivalents.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm install eslint --save-dev
```

Next, install `eslint-plugin-jquery`:

```
$ npm install eslint-plugin-jquery --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-jquery` globally.

## Usage

Add `jquery` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": [
    "jquery"
  ],
  "rules": {
    "jquery/no-ajax": 2,
    "jquery/no-class": 2,
    "jquery/no-closest": 2,
    "jquery/no-data": 2,
    "jquery/no-deferred": 2,
    "jquery/no-each": 2,
    "jquery/no-find": 2,
    "jquery/no-html": 2,
    "jquery/no-inarray": 2,
    "jquery/no-map": 2,
    "jquery/no-param": 2,
    "jquery/no-parent": 2,
    "jquery/no-parents": 2,
    "jquery/no-serialize": 2,
    "jquery/no-text": 2,
    "jquery/no-trigger": 2,
    "jquery/no-trim": 2,
    "jquery/no-val": 2,
    "jquery/no-wrap": 2
  }
}
```

## Development

```
npm install
npm test
```

## License

Distributed under the MIT license. See LICENSE for details.
