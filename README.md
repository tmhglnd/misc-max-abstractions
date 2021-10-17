# misc-max-abstractions

A variety of max abstractions that can be helpful during patching but don't really fit any category.

Timo Hoogland (c) 2019 www.timohoogland.com

## Contains

- **!pow** - *Raise the right inlet to power of the left inlet*

- **benchmark** - *Test the speed of an algorithm over multiple iterations*

- **cputimer** - *Return a precise time interval between two events*

- **ctlfox** - *Input and store/recall Faderfox EC4 controller values, works with high-resolution LSB/MSB MIDI, allows scaling of 0 - 16384 hires range*

- **ezbiquad~** - *Biquad~ and Filtercoeff~ wrapped in one object*

- **fft.tomatrix~** - *Store a FFT-frame in a jitter matrix*

- **fullscreen** - *Short-keys for the jit.world*

- **hidecursor** - *Hide the cursor when idle for three seconds*

- **jit.gl.snapshot** - *Export an image of a texture or matrix from jit.world with a single bang*

- **mira.port.web** - *launch mira.frame in the browser on localhost with a bang*

- **msbalance~** - *change the balance of mid/side information in a stereo signal*

- **monostereo~** - *change the balance of mono/stereo in a stereo signal*

- **pause~** - *Allow for a feedback-loop between msp objects, introduces 1 signalvector latency*

- **r~** - *Abbreviated abstraction for receive~* **deprecated as of Max 8.2**

- **s~** - *Abbreviated abstraction for send~* **deprecated as of Max 8.2**

- **sign~** - *Return the sign of a signal*

- **squash~** - *Simple audio signal compression/squashing (based on patch by Peter McCulloch)*

- **uniquename** - *Generate a unique name based on time + ticks*

## Install

```
1. download zip 
2. unzip in Max searchpath (eg. on MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max searchpath (eg. on MacOS cd ~/Documents/Max\ 8/Library)
3. $ git clone https://github.com/tmhglnd/misc-max-abstractions.git
```
