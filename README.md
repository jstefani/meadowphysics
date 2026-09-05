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

Monobright hardware (40h, pre-2011 series 64/128/256) only lights leds above
a brightness threshold, so the dim levels this script draws never show.
PARAMS > `use monobright grid` defaults to `auto`, which
detects those models from the grid's serial. If detection misses your grid,
set it to `yes`; `no` forces varibright drawing. In monobright mode the
playhead, selection, status and rule glyphs are drawn at full brightness and
dim hints/ranges are turned off. Varibright drawing is otherwise untouched.

## midi out and nbout

`midi out device` lists every norns midi port by number and name, including
the virtual `nb` port added by the [nbout](https://github.com/sixolet/nbout)
mod. Pick the port named `nb` (or assign `nb` to a slot in SYSTEM > DEVICES >
MIDI and pick that slot) and set `output` to `midi`. nbout only listens on
midi channel 1, so leave `midi out channel` at 1 and per-voice channels at
their default.
