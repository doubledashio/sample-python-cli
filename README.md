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


## Sample output
<img src="https://github.com/Dracaltech/sample-python-cli/assets/1357711/44e35d8a-152f-4424-a3e2-dfc427c38c2b" width=400 />

```
Ξ dracal/sample-python-cli git:(develop) ▶ python main.py
Temperature (C): 100.43
RH......... (%): 23.93
Pressure..(kPa): 53.01
Temperature (F): 212.77400000000003
Ξ dracal/sample-python-cli git:(develop) ▶
```
