There are three test cases that use the init()/step!() interface in the V3Kite examples folder. Simulation results are presented here.
## simple_parking.jl

[[Fix V3Kite/simple_parking/Baseline|Baseline]] with dt = 0.05/3, ripple RMS =  0.0292 °

[[High pulley damping]] with PULLEY_DAMPING = 10.0, ripple RMS  = 0.0164 ° 

[[Low pulley damping]] with PULLEY_DAMPING = 2.0, ripple RMS =  0.0403 °

[[DT 10ms]] ripple RMS =  0.0357 °

[[DT 50ms]] ripple RMS =   0.0341 ° 

The only test that improved the RMS value was high pulley damping.

## simple_auto_parking.jl

[[Fix V3Kite/simple_auto_parking/Baseline|Baseline]] with dt = 0.05/3. ripple RMS = 0.0134 °

[[Fix V3Kite/simple_auto_parking/DT 50ms|DT 50ms]] with dt = 0.05. ripple RMS = 0.0135 ° 

## simple_sinus.jl

[[Fix V3Kite/simple_sinus/Baseline|Baseline]] with dt = 0.05/3, AERO_MODE = AeroDirect(): Good

[[Baseline_continues]] with dt = 0.05/3, AERO_MODE = Continues(): Very bad oscillations

[[Baseline_continues_VSM3]] with dt = 0.05/3, AERO_MODE = Continues(), VSM_INTERVAL = 3: Good

