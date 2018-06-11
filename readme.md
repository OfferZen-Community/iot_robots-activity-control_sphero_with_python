### Make: IoT Robots

<img src="/images/python-logo.png" width="80" height="80" align="right" />
# Control Sphero with Python

## Getting Started

To control Sphero with Python, we'll can use:

https://github.com/CMU-ARM/sphero_sprk


The following is some sample code to get you started:

```python
from sphero_sprk import Sphero

orb = Sphero("XX:XX:XX:XX:XX:XX")
orb.connect()

orb.set_rgb_led(255,0,0)
orb.roll(100,0)
```


## Other Notes

There are actually several Python libraries to control Sphero, but this one definitely works :). Please take note that it <b> doesn't work on Mac </b> because of compatibility issues with the `bluepy` library.

