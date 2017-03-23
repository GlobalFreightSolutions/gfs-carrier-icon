[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-icon.svg?branch=master)](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-icon)


# &lt;gfs-carrier-icon&gt;

[Live Demo](http://codepen.io/globalfreight/pen/b8bd321a0f5e67df4081836a3f93809f)

The `gfs-carrier-icon` widget is used by the other widgets in the GFS Checkout collection, but is also available to use for display of carrier icons within your eCommerce website.


## Install

```bash
# via bower
$ bower install gfs-carrier-icon
```

## Usage
```html
<link rel="import" href="path_to_bower_components/gfs-carrier-icon/gfs-carrier-icon.html" />
```

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


### License

Apache License 2.0