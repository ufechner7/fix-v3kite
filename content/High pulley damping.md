
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 10.0 

Run simple_parking.jl

**Result:**

AoA ripple, t = 2.02 .. 10.00 s, 480 samples at 60.0 Hz
  ripple RMS         :   0.0164 °  (detrended)
  ripple pk-pk       :   0.1675 °  (detrended)
  PSD peak           :     5.12 Hz (resolution 0.12 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.141 °
  mean elevation     :   78.090 °
  mean tether force  :   1323.9 N

![[Pasted image 20260811121239.png]]




