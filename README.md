# [<tt>tape</tt>](https://s9a.github.io/tape)

#### [<tt>seek releases</tt>](../../releases) or <code><a href="https://docs.npmjs.com/cli">npm install</a> <a href="https://npm.im/@s9a/tape">@s9a/tape</a></code>

## [`tape.css`](tape.css)

## palette

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

## compose

- `.tape-flow` flow color within scope
- `.tape-skip` skip color within flow
- `.tape-flat` border `transparent`
- `.tape-flap` border `currentColor`
- `.tape-erase` erase text for screenshot art

## [`var`](tape.css)

- `--tape-black`
- `--tape-white`
- `--tape-pink` warm
- `--tape-yellow` fresh
- `--tape-green` lush
- `--tape-blue` cool
- `--tape-hex` is current neon
- `--tape-mix` is current background color
- [`--tape-remix`](#imagine) imagine
- [`--tape-filter`](#filter) hue

## [samples](https://s9a.page)

### tape page

```html
<html class="tape-flow tape-black">
```

### tape anywhere

```html
<aside class="tape-yellow">
  <em>So</em> fresh!
</aside>
```

### cool quote
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

### black link

```html
<a class="tape-black" href="https://s9a.page/tape">tape</a>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-black" href="https://s9a.page/tape">tape</a>
</aside>
```

### pink link

```html
<a class="tape-pink" href="https://s9a.page/tape">tape</a>
```

```html
<aside class="tape-pink tape-flow">
  Stick 4ever.
  Apply <a href="https://s9a.page/tape">tape</a>
</aside>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-flow" href="https://s9a.page/tape">tape</a>
</aside>
```

### prime action

```html
<fieldset class="tape-flat tape-black">
  <button class="tape-flap tape-green">Save</button>
  <button class="tape-flap tape-flow">Cancel</button>
</fieldset>
```

### creative tone

```html
<fieldset class="tape-pink">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Imagine :)</strong>
  </label>
</fieldset>
```

### sting tone

```html
<fieldset class="tape-yellow">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Taken :(</strong>
  </label>
</fieldset>
```

### peace tone

```html
<fieldset class="tape-blue">
  <label>
    <b>Create name</b>
    <input class="tape-white">
    <strong>Yes =)</strong>
  </label>
</fieldset>
```

## [imagine](https://developer.mozilla.org/CSS/gradient)

```css
:root {
  --tape-remix: radial-gradient(coral, violet);
}
```

## [filter](https://developer.mozilla.org/CSS/filter)

```css
:focus {
  --tape-filter: invert(100%);
}

:link:hover {
  --tape-filter: hue-rotate(120deg);
}
```

```css
.twist {
  --tape-filter: hue-rotate(120deg);
}

.shout {
  --tape-filter: hue-rotate(240deg);
}
```

## [testing](https://webmural.com/testing)

[<tt>tape online</tt>](https://s9a.page/tape) [**sans shame**](https://webmural.com/shame)
