## Incubox Foundation SumoSelect

### Getting Started

After cloning locally, go inside the repository in the terminal. Then type the following command:

```
$ npm install
$ bower update
```

After the downloading the packages, you can test the plugin by typing:

```
$ gulp watch
```

That will open your browser with the demo.

### Usage

To use it inside your application, add the ```sumoselect.css``` after foundation, in your html:

```html
<link rel="stylesheet" href="foundation.min.css"/>
<link rel="stylesheet" href="sumoselect.css"/>
```

and the ```jquery.sumoselect.js``` after the ```jQuery``` and ```Foundation```:

```html
<script src="jquery.min.js"></script>
<script src="foundation.min.js"></script>
<script src="jquery.sumoselect.js"></script>
```

Then initialized:

```html
<script>
  $('select.SumoSelect').SumoSelect({
    okCancelInMulti: true
  });
</script>
```