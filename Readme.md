[![CircleCI](https://circleci.com/gh/GlobalFreightSolutions/gfs-carrier-icon/tree/v2.preview.svg?style=svg)](https://circleci.com/gh/GlobalFreightSolutions/gfs-carrier-icon/tree/v2.preview)

# &lt;gfs-carrier-icon&gt;

The `gfs-carrier-icon` widget is used by the other widgets in the GFS Checkout collection, but is also available to use for display of carrier icons within your eCommerce website.

## Install

```bash
$ npm i --save @gfsdeliver/gfs-carrier-icon/gfs-carrier-icon.js
```

### Import In a HTML file:

```html
<html>
    <head>
        <script type="module">
            import '@gfsdeliver/gfs-carrier-icon/gfs-carrier-icon.js';
        </script>
    </head>
    <body>
        <gfs-carrier-icon carrier-name="dpd" icon-size="medium" country-code="GB"></gfs-carrier-icon>
    </body>
</html>
```

### In a Polymer 3 element

```js
import { PolymerElement, html } from '@polymer/polymer/polymer-element.js';
import '@gfsdeliver/gfs-carrier-icon/gfs-carrier-icon.js';

class CustomElement extends PolymerElement {
    static get template() {
        return html`
            <gfs-carrier-icon carrier-name="dpd" icon-size="medium" country-code="GB"></gfs-carrier-icon>
        `;
    }
}
customElements.define('custom-element', CustomElement);
```

More info and all the available properties can be found at [GFS widget portal](http://developer.justshoutgfs.com/info/documentation/gfs-checkout/the-gfs-checkout-widgets/carrier-icon-widget/ "The GFS Carrier Icon Widget")


## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)