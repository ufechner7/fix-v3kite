
Depower setpoint: 0.25
dt = 0.01
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0 

Run simple_parking.jl

**Result:**

AoA ripple, t = 2.00 .. 10.00 s, 801 samples at 100.0 Hz
  ripple RMS         :   0.0357 °  (detrended)
  ripple pk-pk       :   0.3254 °  (detrended)
  PSD peak           :     5.37 Hz (resolution 0.12 Hz, Nyquist 50.0 Hz)
  mean AoA (trim)    :    4.139 °
  mean elevation     :   78.102 °
  mean tether force  :   1325.1 N

![[Pasted image 20260811121804.png]]





