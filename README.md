# Polaroidit

Turn any image into an old-school polaroid.

# Installation

`npm i polaroidit --save`

Then...

```
import { polaroidit } from 'polaroidit';
polaroidit({
    shadow_type: 'soft',
    padding: true
});
```

## Options

Polaroidit supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)