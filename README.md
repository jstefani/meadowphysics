# meadowphysics(norns)
https://monome.org/docs/modular/meadowphysics/

https://monome.org/docs/modular/ansible/

--
--   m e a d o w p h y s i c s
--
--   a grid-enabled
--   rhizomatic
--   cascading counter
--
--
--   *----
--        *-----
--            *---
--      *-----
--
--

## keys and encoders

```
hold k1:      alt. k2 play/pause, k3 reset
e1:           tempo (norns clock)
e3:           scroll grid view (8x8 grids only, no-op on a 128)
```

## monobright grids

Using a 40h or series (monobright) grid? Set PARAMS > MEADOWPHYSICS >
`use monobright grid` to `yes`. Monobright hardware only lights leds above a
brightness threshold, so the dim levels this script draws never show. The
option maps playhead, selection, status and rule glyphs to full brightness
and dim hints/ranges to off. Varibright drawing is untouched when it is `no`.
