# sample-node-vcp
Dracal // SDK code sample for Node on CLI

## Assumptions

Running this repository requires you to have installed:
- Python (version >= `3.x`)
- DracalView (version >= `3.2.x`)
  - Specifically, `dracal-usb-get` needs to be accessible from your `PATH` environment variable (more info in the [documentation how-to](https://www.dracal.com/en/programmers_howto/#dracal-usb-get)).

Script may need to be adjusted depending on your instrument's # of outputs _(currently assumed: 3 outputs)_. See script comments for details.

## Simple usage

Run script
```
python main.py
```
