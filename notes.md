# Throttle and Debounce

![Throttle and Debounce pic](/images/Throttle_Debounce.png?raw=true)

- Debounce calls the given function once after the given input stops changing (fires at the end after a given interval passes)

```
window.addEventListener('resize', () => _.debounce( () => console.log(`Only after a second ${window.innerWidth} x ${window.innerHeight}`), 1000))
```

- Throttle limits calls to the function (fires while you're changing but not on every change)

Throttling will fire the requests so you can get the interim results but debouncing will wait until the end.

[interactive demo](http://demo.nimius.net/debounce_throttle/)
