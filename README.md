# Polaroid

Turn any image into an old-school polaroid.

# Installation

`npm i polaroid --save`

Then...

```
import { polaroid } from 'polaroid';
polaroid({
    shadow_type: 'soft',
    padding: true
});
```

## Options

Polaroid supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)