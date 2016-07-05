## three-obj-exporter

This is the Three.js OBJExporter "extras" package found in the [Three.js source](http://threejs.org/examples/js/exporters/OBJExporter.js) ([example](http://threejs.org/examples/webgl_exporter_obj.html)).

It's loosely based on the [three-orbit-controls](https://github.com/mattdesl/three-orbit-controls) package.

## Usage:

```js
var OBJExporter = require('three-obj-exporter');
var exporter = new OBJExporter();
var result = exporter.parse(scene);
```

See [the offical Three.js example](http://threejs.org/examples/webgl_exporter_obj.html) for more information and usage.
