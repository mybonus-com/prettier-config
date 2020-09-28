# @mybonus-com/prettier-config

Prettier configuration for MyBonus.

## Usage

```sh
$ yarn add -D @mybonus-com/prettier-config
```

In `package.json` add:

```js
{
	"prettier": "@mybonus-com/prettier-config"
}
```

Or if you don't want it in your `package.json`:

```sh
$ echo '"@mybonus-com/prettier-config"' > .prettierrc.json
```

Or if you need to extend it, add `.prettierrc.js`:

```js
module.exports = {
	...require("@mybonus-com/prettier-config"),
	// Do your thing...
	semi: false,
};
```
