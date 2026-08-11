
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0 

Run simple_auto_parking.jl

**Result:**
Heading regulation RMS error (t ≥ 10 s): 0.26°, max |e|: 0.27°
Apparent wind speed: mean 12.57 m/s, range 12.50 … 12.59 m/s

AoA ripple, t = 2.02 .. 60.00 s, 3480 samples at 60.0 Hz
  ripple RMS         :   0.0134 °  (detrended)
  ripple pk-pk       :   0.2694 °  (detrended)
  PSD peak           :     5.41 Hz (resolution 0.02 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.217 °
  mean elevation     :   78.165 °
  mean tether force  :   1210.2 N

![[Pasted image 20260811141903.png]]






