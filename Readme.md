[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-icon.svg?branch=develop)](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-icon)


# &lt;gfs-carrier-icon&gt;

[Live Demo](http://codepen.io/globalfreight/pen/b8bd321a0f5e67df4081836a3f93809f)

The `gfs-carrier-icon` widget is used by the other widgets in the GFS Checkout collection, but is also available to use for display of carrier icons within your eCommerce website.

## Install

```bash
# via bower
$ bower install --save gfs-carrier-icon
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/gfs-carrier-icon/gfs-carrier-icon.html">
```

3. Start using it!

<!---
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="gfs-carrier-icon.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<gfs-carrier-icon
    carrier-name="dpd"
    icon-size="medium"
    country-code="GB">
</gfs-carrier-icon>
```

More info and all the available properties can be found at [GFS widget portal](http://gfsdeveloperportal.azurewebsites.net/info/documentation/gfs-checkout/the-gfs-checkout-widgets/carrier-icon-widget/ "The GFS Carrier Icon Widget")


## Testing

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). Install it via:

```bash
$ npm install -g web-component-tester
```

Then, you can run your tests on all of your local browsers via:

```bash
$ wct
```

You can use `wct -p` so you can keep the browsers alive after test runs.

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)