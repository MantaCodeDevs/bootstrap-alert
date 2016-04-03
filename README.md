# bootstrap-alert
A [Bootstrap](http://getbootstrap.com/) addon to display floating alerts.

TODO:
* documentation
  * add screenshots to basic usage
* make sure that element is removed when it is closed
* check if it works on different browsers

## Download

## Installation
Load the library after you load the bootstrap script file.
```html
<script type="text/javascript" src="jQuery.min.js"></script>
<script type="text/javascript" src="bootstrap.min.js"></script>
<script type="text/javascript" src="bootstrap-alert.min.js"></script>
```

## Basic usage
```javascript
BootstrapAlert.info({
  title: "Getting started!",
  message: "See the detailed options below."
});
```

```javascript
BootstrapAlert.warning({
  title: "Bootstrap is required!",
  message: "The library depends on Bootstrap and jQuery."
});
```

```javascript
BootstrapAlert.success({
  title: "All good!",
  message: "Star the repo if you enjoy it."
});
```

```javascript
BootstrapAlert.alert({
  title: "Something went wrong!",
  message: "Raise an issue in the issue tracker if you find a bug."
});
```
## Options
The following options can be passed to each BootstrapAlert method:

| Name | Type | Default | Description |
| ---- | ---- | ------- | ----------- |
| autoHide | boolean | true | If `true` the alert will disappear after the timeout specified in the `hideTimeout` option |
| hideTimeout | number | 3000 | The timeout used in milliseconds to hide the alert when `autoHide` is `true` |
| dissmissible | boolean | false | Controls whether a close button should be added to the alert |
| parentClass | string | 'bootstrap-alert' | The class added to the outer HTML element that is created for the alert |
| innerClass | string | 'bootstrap-alert-message' | The class added to the inner HTML element that contains the alert content |
| title | string | '' | The tilte displayed on the alert |
| message | string | '' | The message displayed after the `title` on the alert |

## License
MIT
