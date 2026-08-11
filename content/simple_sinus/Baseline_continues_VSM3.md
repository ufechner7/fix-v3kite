
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0

AERO_MODE = ContinuousAero()
VSM_INTERVAL = 3

Run simple_sinus.jl

**Result:**

Heading tracking RMS error (t ≥ 30 s): 0.73°

AoA ripple, t = 30.02 .. 120.00 s, 5400 samples at 60.0 Hz
  ripple RMS         :   0.0077 °  (detrended)
  ripple pk-pk       :   0.0458 °  (detrended)
  PSD peak           :     5.67 Hz (resolution 0.01 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.190 °
  mean elevation     :   76.663 °
  mean tether force  :   1281.9 N
wall clock
  mean per step!     :    11.36 ms
  real-time factor   :    1.467  (120.00 s simulated in 81.80 s)

![[Pasted image 20260811150000.png]]







