# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i epicaly.js --save`

Then...

```
import { epicaly } from 'epicaly';

epicaly({
   shadow_type: 'soft',
   padding: false
});
```

## Options

epicaly supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _booLean_ (Defaults to false)