
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0

AERO_MODE = ContinuousAero()

Run simple_sinus.jl

**Result:**

Heading tracking RMS error (t ≥ 30 s): 0.99°

AoA ripple, t = 30.02 .. 120.00 s, 5400 samples at 60.0 Hz
  ripple RMS         :   1.8952 °  (detrended)
  ripple pk-pk       :  31.7402 °  (detrended)
  PSD peak           :    18.42 Hz (resolution 0.01 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    3.818 °
  mean elevation     :   75.705 °
  mean tether force  :   1545.1 N

![[Pasted image 20260811145555.png]]







