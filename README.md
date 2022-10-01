# [<tt>tape</tt>](https://s9a.page/tape)

#### [<tt>seek releases</tt>](../../releases) or <code><a href="https://docs.npmjs.com/cli">npm install</a> <a href="https://npm.im/@s9a/tape">@s9a/tape</a></code>

## [`tape.css`](tape.css)

## [palette](https://s9a.page/tape)

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

## [compose](https://s9a.page/tape#compose)

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

### tape flow

```html
<html class="tape-flow tape-black">
```

having `tape-flow` on your root or body to flow color thru the whole page

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
<a class="tape-black" href="#sample">tape</a>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-black" href="#sample">tape</a>
</aside>
```

### neon link

```html
<a class="tape-pink" href="#sample">tape</a>
```

```html
<aside class="tape-pink tape-flow">
  Stick 4ever.
  Apply <a href="#sample">tape</a>
</aside>
```

```html
<aside class="tape-pink">
  Stick 4ever.
  Apply <a class="tape-flow" href="#sample">tape</a>
</aside>
```

### freestyle

```html
<a href="#sample" class="tape-pink" style="--tape-hex:hotpink">hotpink</a>
```

```html
<nav class="tape-flow" style="--tape-pink:deeppink">
  <a href="#sample" class="tape-pink">deeppink</a>
</nav>
```

### creative tone

```html
<label class="tape-pink">
  <b>Create name</b>
  <input class="tape-white">
  <strong>Imagine :)</strong>
</label>
```

### sting tone

```html

<label class="tape-yellow">
  <b>Create name</b>
  <input class="tape-white">
  <strong>Taken :(</strong>
</label>
```

### peace tone

```html
<label class="tape-blue">
  <b>Create name</b>
  <input class="tape-white">
  <strong>Yes =)</strong>
</label>
```

### saving grace

```html
<button class="tape-flap tape-green">Save</button>
<button class="tape-flap tape-flow">Cancel</button>
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
