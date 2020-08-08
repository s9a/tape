# tape
[<tt><b>colors that stick.</b></tt>](https://s9a.github.io/tape/) [<b>`@latest`</b>](https://unpkg.com/@s9a/tape@latest) `npm install @s9a/tape`

<code>&lt;link rel="stylesheet" href="<strong>...</strong>tape.css"&gt;</code>

## [`tape.css`](tape.css)

### palette

- `.tape-white` black on white
- `.tape-yellow` black on yellow
- `.tape-pink` black on pink
- `.tape-blue` black on blue
- `.tape-green` black on green
- `.tape-black` parent on black
- `.tape-black.tape-white` white on black
- `.tape-black.tape-yellow` yellow on black
- `.tape-black.tape-pink` pink on black
- `.tape-black.tape-blue` blue on black
- `.tape-black.tape-green` green on black

### behavior

**composable mods.** Remember to style interactive elements with visual affordance. Link underline etc.

- `.tape-clean` Let tape color flow deep within scope
- `.tape-clash` Don't clean this element
- `.tape-flat` Make border `transparent`
- `.tape-flap` Make border `currentColor`

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

#### black link

```html
<a class="tape-black" href="https://s9a.github.io/tape/">tape</a>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-black" href="https://s9a.github.io/tape/">tape</a>
</aside>
```

#### pink link

```html
<a class="tape-pink" href="https://s9a.github.io/tape/">tape</a>
```

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

#### primary action

```html
<fieldset class="tape-flat tape-black">
  <button class="tape-flap tape-green">Save</button>
  <button class="tape-flap tape-clean">Cancel</button>
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
