# meadowphysics(norns)
https://monome.org/docs/modular/meadowphysics/

https://monome.org/docs/modular/ansible/

```
k2:  toggle between meadowphysics and scale mode^
k3:  save meadowphysics data to `data/mp.data`
k3^: save scales data to  `data/gridscales.data`
e2:  change root note
e3:  bpm change
```

Using a monobright grid (40h, series)? Set PARAMS > `use monobright grid` to
`yes`. Monobright hardware only lights leds above a brightness threshold, so
the dim levels this script uses never show. The option remaps dim to off and
everything else to full; varibright levels are untouched when it is `no`.
