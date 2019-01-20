### progressbar.js
---
https://github.com/kimmobrunfeldt/progressbar.js

```js
var ProgressBar = require('progressbar.js');
var bar = new ProgressBar.Line('#container', {easing: 'easeInOut'});
bar.animate(1);

```

```js
var ProgressBar = require('progressbar.js');
var line = new ProgressBar.Line('#container');

require.config({
  paths: {'progressbar': '../bower_components/progressbar.js/dist/progressbar'}
});
define(['progressbar'], function(ProgressBar){
  var line = new ProgressBar.Line('#container');
});

var line = new ProgressBar.Line('#container');

var circle = new ProgressBar.Circle('#example-perent-container', {
  color: '#FCB03C',
  strokeWidth: 3,
  trailWidth: 1,
  text: {
    value: '0'
  }
});

var progressBar = new ProgressBar.Circle('#container', {
  strokeWidth: 2
});

progressBar.animate(0.3, {
  duration: 800
}, function(){
  console.log('Animation has finished');
});

var svgPath = document.getElementById('heart-path');
var path = new ProgressBar.Path(svgPath, {
  duration: 300
});

var heart = document.getElementById('heart');
heart.addEventListener('load', function(){
bar path = new ProgressBar.Path(hearObject.contentDocument.querySelector('#heart-path'), {
  duration: 300
});

path.animate(0.3, {
  duration: 800
}, function(){
  console.log('Animation has finished');
});

var bar = new ProgressBar.Line('#container', {
  from: { color: '#000'},
  to: { color: '#888'},
  step: function(state, bar, attachment){
    bar.path.setAttribute('stroke', state.color);
  }
});

var bar = new ProgressBar.Line('#container', {
  step: function(state, bar, attachment){
    bar.path.setattribute('stroke', state.color);
  }
});

function(state, shape, attachment){
  shape.path.setAttribute('stroke-width', state.width);
  shape.path.setAttribute('stroke', state.color);
  attachment.textinnerHTML = shape.value() * 100;
}
```

```css
#container {
  width: 300px;
  height: 150px;
}

{
  color: '#3a3a3a',
  strokeWidth: 2.1,
  trailColor: '#f4f4f4',
  trailWidth: 0.8,
  svgStyle: {
    display: 'block',
    width: '100%'
  },
  text: {
    value: 'text',
    clasName: 'progressbar__label',
    style: {
      color: '#f00',
      position: 'absolute',
      left: '50%',
      top: '50%',
      padding: 0,
      margin: 0,
      transform: {
        prefix: true,
        value: 'translate(-50%, -50%)'
      }
    },
    autoStyleContainer: true,
    alignToBottom: true
  },
  fill: 'rgba(0, 0, 0, 0.5)',
  duration: 1200,
  easing: 'easeOut',
  from: { color: '#eee' },
  to: { color: '#000' },
  step: function(state, circle, attachment){
    circle.path.setAttribute('stroke', state.color)
  },
  warnings: false
}

{
  duration: 1200,
  easing: 'easeInOut',
  from: { color: '#eee' },
  to: { color: '#000' },
  step: function(state, circle, attachment){
    circle.path.setAttribute('stroke', state.color);
  }
}
```


```
npm install
npm install -g watchify
npm install -g browserify

npm install -g mocha
npm install -g testem
```

