#Unicorn HAT

64 blindingly bright LEDs packed into a HAT and driven with an ultra-fast, C library that you can talk to
from Python make Unicorn HAT PiGlow's bigger, brighter brother.

Note: Unicorn HAT uses some special PWM trickery, performed with the same hardware that lets you Pi produce sound
through the audio jack ( analog audio ) so you can't use both at the same time!

Setup is easy, just:

```bash
curl get.pimoroni.com/unicornhat | bash
```

Then import it into your Python script and start tinkering:

```bash
import unicornhat
unicornhat.set_pixel(0, 0, 255, 255, 255)
unicornhat.show()
```