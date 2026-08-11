## simple_parking.jl

[[Baseline]] with dt = 0.05/3, ripple RMS =  0.0292 °

[[High pulley damping]] with PULLEY_DAMPING = 10.0, ripple RMS  = 0.0164 ° 

[[Low pulley damping]] with PULLEY_DAMPING = 2.0, ripple RMS =  0.0403 °

[[DT 10ms]] ripple RMS =  0.0357 °

[[DT 50ms]] ripple RMS =   0.0341 ° 

The only test that improved the RMS value was high pulley damping.

## simple_auto_parking.jl

[[Baseline]] with dt = 0.05/3. ripple RMS = 0.0134 ° 

[[Fix V3Kite/simple_auto_parking/DT 50ms|DT 50ms]] with dt = 0.05. ripple RMS = 0.0135 ° 