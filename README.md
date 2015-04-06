# cocover.js

`cocover.js` is a jQuery plugin that make `mouseover/mouseenter` work while dragging an element.

*What Can I Do With This Plugin*

Make elements sortable easily?

When dragging an element over another element which has attached an `mouseenter/mouseover` event, the
event wont triggered. So if you want to make that work, you must calculate all the element's coordinate
while mouse move, if the elements is few, that's ok, but if the elements is huge, you have to for loop many
times in every mouse move, that's not efficient.

## API

### #over

Chose what elements to be over while dragging an element.

```javascript
cocover.over('.item');
// or $('.item').cocover('over');
```

### #destroy

Destroy this ability.

```javascript
cocover.destroy('.item');
// or $('.item').cocover('destroy');
```

### #start

Only called this method, this plugin can work. 

```javascript
cocover.start();
// or $('.item').cocover('start');
```

### #stop

Stop will make this plugin temporally not work.

```javascript
cocover.stop();
// or $('.item').cocover('stop');
```

## License

MIT License (http://towry.me/mit-license/)

