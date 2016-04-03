# bootstrap-alert
A [Bootstrap](http://getbootstrap.com/) addon to display floating alerts.

TODO:
* documentation
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
BootstrapAlert.alert({
  title: "Something went wrong!",
  message: "Try it again."
});
```
```javascript
BootstrapAlert.info({
  title: "Getting started!",
  message: "Check the different flavors below"
});
```



```javascript
BootstrapAlert.warning({
  title: "Something went wrong.",
  message: "Please try again"
});
```

```javascript
BootstrapAlert.success({
  title: "Great!",
  message: "Star the repo if you enjoy it."
});
```
## Options

## License
MIT
