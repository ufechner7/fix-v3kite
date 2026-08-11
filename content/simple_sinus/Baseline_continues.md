
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0

AERO_MODE = ContinuousAero()

Run simple_sinus.jl

**Result:**

Heading tracking RMS error (t ≥ 30 s): 0.99°

AoA ripple, t = 2.00 .. 60.00 s, 1161 samples at 20.0 Hz
  ripple RMS         :   0.0135 °  (detrended)
  ripple pk-pk       :   0.2492 °  (detrended)
  PSD peak           :     5.44 Hz (resolution 0.02 Hz, Nyquist 10.0 Hz)
  mean AoA (trim)    :    4.217 °
  mean elevation     :   78.165 °
  mean tether force  :   1210.8 N

![[Pasted image 20260811145555.png]]







