# What's this?

Get perfect shadows!

First exercise to create a npm library.

Based on a youtube video that currently can't remember, as soon as I can I paste the link.

# Installation

`npm i sombritas --save`

Then...
```
import { sombritas } from "sombritas";

sombritas({
    shadow_type: "soft",
    padding: false
});
```
Sombritas supports 2 optios, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
