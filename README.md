[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/GeoloeG/numbro-element)

# `<numbro-element>`

## Descripton

`<numbro-element>` is a CSS friendly element wrapper for the [numbro.js](http://numbrojs.com/) library.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install numbro-element --save
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/numbro-element/numbro-element.html">
```

And then use it:

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="numbro-element.html">
	  <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<numbro-element value="1000" format="0.0"></numbro-element>
```

See the [Documentation](https://geoloeg.github.io/numbro-element/) for more options.

## More Demos

[https://geoloeg.github.io/numbro-element/](https://geoloeg.github.io/numbro-element/components/numbro-element/demo/)

## Discussing

If you have any questions, you can find me on the [Polymer Slack Channel](https://polymer.slack.com/), or just raise an Issue.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
