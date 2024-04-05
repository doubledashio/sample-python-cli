# sample-python-vcp
Dracal // SDK code sample for Python on CLI

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
<img src="https://github.com/Dracaltech/sample-python-cli/assets/1357711/86251866-40e0-4baf-bcc0-13668f548df6" width=400 />

```
Ξ dracal/sample-python-cli git:(develop) ▶ python main.py
Temperature (C): 21.67
RH......... (%): 56.9
Pressure..(kPa): 101.17
Temperature (F): 71.006
Ξ dracal/sample-python-cli git:(develop) ▶
```
