# xernerx-extension-builder

This is a builder for the xernerx framework. This provides a class builder you can extend.

## Requirements

| property | type   | description                        |
| -------- | ------ | ---------------------------------- |
| name     | string | used to give the extension a name. |

## Example

```js
import ExtensionBuilder from 'xernerx-extension-builder';

export default class YourExtensionName extends ExtensionBuilder {
	constructor(/* any */) {
		super('YourExtensionName');

		/* any */
	}

	/* any */
}
```

## Return

```js
{
	name: 'YourExtensionName';
}
```
