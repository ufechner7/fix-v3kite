There are three test cases that use the init()/step!() interface in the V3Kite examples folder. Simulation results are presented here.
## simple_parking.jl

[Baseline](simple_parking/Baseline.md) with dt = 0.05/3, ripple RMS =  0.0292 °

[High pulley damping](simple_parking/High%20pulley%20damping.md) with PULLEY_DAMPING = 10.0, ripple RMS  = 0.0164 ° 

[Low pulley damping](simple_parking/Low%20pulley%20damping.md) with PULLEY_DAMPING = 2.0, ripple RMS =  0.0403 °

[DT 10ms](simple_parking/DT%2010ms.md) ripple RMS =  0.0357 °

[DT 50ms](simple_parking/DT%2050ms.md) ripple RMS =   0.0341 ° 

The only test that improved the RMS value was high pulley damping.

## simple_auto_parking.jl

[Baseline](simple_auto_parking/Baseline.md) with dt = 0.05/3. ripple RMS = 0.0134 °

[DT 50ms](simple_auto_parking/DT%2050ms.md) with dt = 0.05. ripple RMS = 0.0135 ° 

## simple_sinus.jl

[Baseline](simple_sinus/Baseline.md) with dt = 0.05/3, AERO_MODE = AeroDirect(): Good

[Baseline_continues](simple_sinus/Baseline_continues.md) with dt = 0.05/3, AERO_MODE = ContinuousAero(): Very bad oscillations

[Baseline_continues_VSM3](simple_sinus/Baseline_continues_VSM3.md) with dt = 0.05/3, AERO_MODE = ContinuousAero(), VSM_INTERVAL = 3: Good

