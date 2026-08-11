
Depower setpoint: 0.25
dt = 0.05/3
BODY_DAMPING = [0.0, 0.0, 40.0]
MIN_DAMPING = [0.0, 0.0, 32.0]
PULLEY_DAMPING = 5.0 
DAMPING_PER_STIFFNESS = 0.001
VSM_INTERVAL = 1

Run simple_auto_parking.jl

**Result:**
Heading regulation RMS error (t ≥ 10 s): 0.26°, max |e|: 0.26°
Apparent wind speed: mean 12.57 m/s, range 12.50 … 12.59 m/s

AoA ripple, t = 2.02 .. 60.00 s, 3480 samples at 60.0 Hz
  ripple RMS         :   0.0029 °  (detrended)
  ripple pk-pk       :   0.0532 °  (detrended)
  PSD peak           :     5.34 Hz (resolution 0.02 Hz, Nyquist 30.0 Hz)
  mean AoA (trim)    :    4.216 °
  mean elevation     :   78.163 °
  mean tether force  :   1210.3 N
wall clock
  mean per step!     :     2.14 ms
  real-time factor   :    7.780  (60.00 s simulated in 7.71 s)

![[Pasted image 20260811141903.png]]






