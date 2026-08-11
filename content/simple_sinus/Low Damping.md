
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0

AERO_MODE = AeroDirect()

Run simple_sinus.jl

**Result:**

Heading tracking RMS error (t ≥ 30 s): 0.71°

AoA ripple, t = 30.02 .. 120.00 s, 5400 samples at 60.0 Hz
  ripple RMS         :   0.0034 °  (detrended)
  ripple pk-pk       :   0.0363 °  (detrended)
  PSD peak           :     5.53 Hz (resolution 0.01 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.177 °
  mean elevation     :   76.576 °
  mean tether force  :   1283.6 N
wall clock
  mean per step!     :     2.88 ms
  real-time factor   :    5.797  (120.00 s simulated in 20.70 s)

![[Pasted image 20260811171910.png]]







