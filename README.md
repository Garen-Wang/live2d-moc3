# live2d-moc3


## Usage

Place models in `assets` folder. (e.g. `jiaran4`)

Place images in `images` folder. (e.g. background image)

Then all you need to do is customize the next few lines in `js/bundle.js`:

```javascript
exports.ResourcesPath = 'https://cdn.jsdelivr.net/gh/Garen-Wang/live2d-moc3@vv0.2.0/';
exports.BackImageName = ''; // background image
exports.GearImageName = 'icon_gear.png'; // image of gear for switching models
exports.PowerImageName = 'CloseNormal.png'; // not important
exports.ModelDir = ['jiaran4']; // names of models
```


## Demo

The code will render live2d model in the canvas.

```html
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=1900">
  <title>TypeScript HTML App</title>
  <style>
    html, body {
        margin: 0;
        overflow: hidden;
    }
  </style>
  <script src="https://cdn.jsdelivr.net/gh/Garen-Wang/live2d-moc3@vv0.2.0/js/minified.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/Garen-Wang/live2d-moc3@vv0.2.0/js/live2dcubismcore.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/Garen-Wang/live2d-moc3@vv0.2.0/js/bundle.js"></script>
</head>
<body>
  <canvas width="1452" height="353"></canvas>
</body>
</html>
```


## Use in Your Webpages

```html

```

## Model Reference

- jiaran4: https://www.bilibili.com/video/BV1c54y1e7Bo

## License

The repository is under WTFPL.

