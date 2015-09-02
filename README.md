&lt;juicy-iframe&gt;
==============

`<juicy-iframe>` is a custom element that lets you stamp inline or external HTML into an iframe.
It also provides simple data binding, that works for native JS/HTML as well as for Polymer's `dom-bind`.

## Demo/Examples

[Check it live!](http://juicy.github.io/juicy-iframe/examples/index.html)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install Juicy/juicy-iframe --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-iframe/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill, if needed:

	```html
	<script src="bower_components/webcomponentsjs/webcomponents.js">
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-iframe/juicy-iframe.html">
    ```

3. Start using it!

    ```html
    <template is="juicy-iframe" content="./your/partial.html"></template>
    ```

## Options/Attributes

Attribute    | Options           | Default     | Description
---          | ---               | ---         | ---
`content`    | *String*		     | `""`	       | Safe HTML code, or path (starts with `/` or `./`) to partial to be loaded.
`model`      | *String* or *Object* | `undefined` | Data model to attach to stamped iframe.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-iframe/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
