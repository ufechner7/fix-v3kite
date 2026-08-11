
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
  ripple RMS         :   0.0129 °  (detrended)
  ripple pk-pk       :   0.0869 °  (detrended)
  PSD peak           :     5.51 Hz (resolution 0.01 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.179 °
  mean elevation     :   76.579 °
  mean tether force  :   1283.8 N
wall clock
  mean per step!     :     7.74 ms
  real-time factor   :    2.153  (120.00 s simulated in 55.72 s)

![[Pasted image 20260811145103.png]]







