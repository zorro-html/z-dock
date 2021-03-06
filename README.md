# `<z-dock>`

Dock-style layout, which is possible to have four-side bars to attach to.

- `<z-dock-main>`: main block in the center
- `<z-dock-left>`: bar on the left of main block
- `<z-dock-right>`: bar on the right of main block
- `<z-dock-top>`: bar on the top of main block
- `<z-dock-bottom>`: bar on the bottom of main block

## Import

```
<link rel="import" href="z-dock/z-dock.html">
```

## Examples

```
<style>
  z-dock[case="z-dock"] {width: 200px; height: 200px; margin-bottom: 30px;}
  [case="z-dock"] z-dock-top,
  [case="z-dock"] z-dock-bottom {height: 30px; background: #ccc;}
  [case="z-dock"] z-dock-left,
  [case="z-dock"] z-dock-right {width: 30px; background: #ddd;}
  [case="z-dock"] z-dock-main {background: #eee;}
</style>

<z-dock case="z-dock">
  <z-dock-top></z-dock-top>
  <z-dock-left></z-dock-left>
  <z-dock-main></z-dock-main>
</z-dock>

<z-dock case="z-dock">
  <z-dock-top></z-dock-top>
  <z-dock-right></z-dock-right>
  <z-dock-bottom></z-dock-bottom>
  <z-dock-main></z-dock-main>
</z-dock>

<z-dock case="z-dock">
  <z-dock-top></z-dock-top>
  <z-dock-left></z-dock-left>
  <z-dock-right></z-dock-right>
  <z-dock-bottom></z-dock-bottom>
  <z-dock-main></z-dock-main>
</z-dock>
```
