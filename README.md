# tape
[<tt><b>colors that stick.</b></tt>](https://s9a.github.io/tape/)

## [`tape.css`](tape.css)

### palette

- `.tape-white` black on white
- `.tape-yellow` black on yellow
- `.tape-pink` black on pink
- `.tape-blue` black on blue
- `.tape-green` black on green
- `.tape-black` parent on black

### behavior

**composable mods.** Remember to style interactive elements with visual affordance. Link underline etc.

- `.tape-clean` Override coloring within
- `.tape-unclean` Override `.tape-clean` on specific element
- `.tape-flat` Transparentize borders within
- `.tape-unflat` Override `.tape-flat` on specific element

### examples

#### tape page

```html
<html class="tape-white">
```

#### tape anywhere

```html
<aside class="tape-yellow">
  <em>So</em> fresh!
</aside>
```

#### black link
```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-black" href="https://s9a.github.io/tape/">tape</a>
</aside>
```

#### pink link

```html
<aside class="tape-pink tape-clean">
  Stick 4ever.
  Apply <a href="https://s9a.github.io/tape/">tape</a>
</aside>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-clean" href="https://s9a.github.io/tape/">tape</a>
</aside>
```

#### cool quote
```html
<blockquote class="tape-blue">
  I said empty your mind.
  Be formless.
  Shapeless.
  Like tape.
  Now you put tape onto walls, it becomes the walls.
  You put tape onto floors, it becomes the floors.
  You put it in you, it becomes yours.
  Now tape can flow or it can shred.
  Be tape my friend.
</blockquote>
```

#### primary action

```html
<fieldset class="tape-white">
  <button class="tape-black">Save</button>
  <button>Cancel</button>
</fieldset>
```

```html
<fieldset class="tape-flat tape-white">
  <button class="tape-unflat tape-black">Save</button>
  <button class="tape-unflat">Cancel</button>
</fieldset>
```

#### creative tone

```html
<fieldset class="tape-yellow">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Imagine :)</strong>
  </label>
</fieldset>
```

#### denial tone

```html
<fieldset class="tape-pink">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Taken :(</strong>
  </label>
</fieldset>
```

#### success tone

```html
<fieldset class="tape-green">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Yes =)</strong>
  </label>
</fieldset>
```

[<tt><b>tape online. :D</b></tt>](https://s9a.github.io/tape/)
