
Depower setpoint: 0.25
dt = 0.05
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0 

Run simple_parking.jl

**Result:**

AoA ripple, t = 2.00 .. 10.00 s, 161 samples at 20.0 Hz
  ripple RMS         :   0.0341 °  (detrended)
  ripple pk-pk       :   0.2374 °  (detrended)
  PSD peak           :     5.47 Hz (resolution 0.12 Hz, Nyquist 10.0 Hz)
  mean AoA (trim)    :    4.140 °
  mean elevation     :   78.110 °
  mean tether force  :   1326.5 N

![[Pasted image 20260811121959.png]]





