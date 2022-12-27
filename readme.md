# Simple SVG

[Modern browsers now support svg for favicon](https://web.dev/building-an-adaptive-favicon/#:~:text=A%20custom%20favicon%20is%20a,of%20SVG%2C%20a%20vector%20format.
  URL: https://web.dev/building-an-adaptive-favicon/#:~:text=A%20custom%20favicon%20is%20a,of%20SVG%2C%20a%20vector%20format)

Also it's very common to build square or circle images holding a single alphabetic upper case letter for user profiles, website logos, etc.

Given this need, this repo provides some common sq.svg and a c.svg for such needs.

## How to use

For a square, if you do not provide any parameters, this is the query

```
sq.svg
```

You will get

For a circle, if you do not provide any parameters, this is the query

```
c.svg
```

You will get


### Parameters

There are only 3 paramters that apply to both sq.svg and c.svg.

- size or s default is 512px
- text or t default is A
- color or c default is 000000

#### Size (s)

There are only the following sizes applicable in px: 512, 256, 128, 64, 48, 32, 16

Default is 512

Any illegal values, will just default back to 512.

#### Text (t)

Only uppercase allowed.

Regardless of length, only use the first character.

Any illegal values, will just default back to A.

#### Color (c)

Only hex color values like 000000 allowed.

#### An example how to use parameters


For a square,

```
sq.svg?color=881337&t=s&s=256
```

You will get

For a circle,

```
c.svg?color=881337&t=s&s=256
```