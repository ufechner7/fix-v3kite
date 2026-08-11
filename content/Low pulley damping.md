
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 2.0 

Run simple_parking.jl

**Result:**

AoA ripple, t = 2.02 .. 10.00 s, 480 samples at 60.0 Hz
  ripple RMS         :   0.0403 °  (detrended)
  ripple pk-pk       :   0.3596 °  (detrended)
  PSD peak           :     5.50 Hz (resolution 0.12 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.141 °
  mean elevation     :   78.109 °
  mean tether force  :   1323.6 N

![[Pasted image 20260811121452.png]]





