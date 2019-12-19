# eslint-plugin-no-setter-return

this plugin provides a new rule which disallow return statement in setter function

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-no-setter-return`:

```
$ npm install eslint-plugin-no-setter-return --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-no-setter-return` globally.

## Usage

Add `no-setter-return` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "no-setter-return"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "no-setter-return/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





