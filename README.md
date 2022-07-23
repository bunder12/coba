## coba
`npm start`

| Coba | Coba2 |
|------------|----------|
| nama sitsu | nama situs1|

```js
const effect = VANTA.WAVES({
  el: '#my-background',
  color: 0x000000
})

// Later, when you want to update an animation in progress with new options
effect.setOptions({
  color: 0xff88cc
})

// Later, if the container changes size and you want to force Vanta to redraw at the new canvas size
effect.resize()
```

