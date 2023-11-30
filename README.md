# Triton
Flight Tracker

parameters = {
    # Mass Details
    "rocket_mass": (21.525, 0.010), # Rocket dry mass: 20.846 kg
    # propulsion details
    "motor_structure_mass": (8.064, 0.1),
    "burn_time": (3.9, 0.1),
    "nozzle_radius": (0.049, 0.001),
    "throat_radius": (0.049, 0.001),
    "grain_separation": (0.002, 0.001),
    "grain_density": (908.907, 30),
    "grain_outer_radius": (0.033, 0.001),
    "grain_initial_inner_radius": (0.015, 0.002),
    "grain_initial_height": (0.12, 0.001),
    "grains_center_of_mass_position": (-0.35, 0.100),
    "nozzle_position": (0, 0.100),
    "motor_position": (3.391, 0.100),
    # aerodynamic details
    "center_of_mass_without_motor": (1.3, 0.100),
    "drag_coefficient": (0.44, 0.1),
    "inertia_i": (73.316, 0.3 * 73.316),
    "inertia_z": (0.15982, 0.3 * 0.15982),
    "radius": (0.1015, 0.001),
    "power_off_drag": (1, 0.033),
    "power_on_drag": (1, 0.033),
    ## nose cone
    "nose_length": (0.5, 0.001),
    "nose_radius": (0.15, 0.001),
    "nose_position": (0, 0.100),
    ## fins
    "fin_span": (0.13, 0.001),
    "fin_root_chord": (0.30, 0.001),
    "fin_tip_chord": (0.11, 0.001),
    "fin_sweep_angle": (49.09, 0.5),
    "fin_position": (3.050, 0.100),
    ## transitions
    "radius": (0.15, 0.010),
    # launch and environment details
    "wind_direction": (0, 3),
    "wind_speed": (1, 0.30),
    "inclination": (90, 1),
    "heading": (181, 3),
    "rail_length": (5.2, 0.001),
    # parachute details
    "cd_s_drogue": (1.5 * np.pi * (24 * 25.4 / 1000) * (24 * 25.4 / 1000) / 4, 0.1),
    "cd_s_main": (2.2 * np.pi * (120 * 25.4 / 1000) * (120 * 25.4 / 1000) / 4, 0.1),
    "lag_rec": (1, 0.5),
}

Environment Condition :
Gravity Details

Acceleration of gravity at surface level:    9.8100 m/s²
Acceleration of gravity at  11.628 km (ASL): 9.8100 m/s²


Launch Site Details

Launch Date: 2019-08-10 21:00:00 UTC
Launch Site Latitude: -23.36361°
Launch Site Longitude: -48.01139°
Reference Datum: SIRGAS2000
Launch Site UTM coordinates: 192123.24 W    7413017.14 S
Launch Site UTM zone: 23K
Launch Site Surface Elevation: 668.0 m


Atmospheric Model Details

Atmospheric Model Type: Ensemble
Ensemble Maximum Height: 11.628 km
Ensemble Time Period: From  2019-08-10 12:00:00  to  2019-08-10 21:00:00  UTC
Ensemble Hour Interval: 3  hrs
Ensemble Latitude Range: From  -20.0 ° To  -26.0 °
Ensemble Longitude Range: From  -50.0 ° To  -45.0 °
Number of Ensemble Members: 10
Selected Ensemble Member: 0  (Starts from 0)


Surface Atmospheric Conditions

Surface Wind Speed: 3.27 m/s
Surface Wind Direction: 324.72°
Surface Wind Heading: 144.72°
Surface Pressure: 943.06 hPa
Surface Temperature: 300.76 K
Surface Air Density: 1.092 kg/m³
Surface Speed of Sound: 347.65 m/s


Earth Model Details

Earth Radius at Launch site: 6374.80 km
Semi-major Axis: 6378.14 km
Semi-minor Axis: 6356.75 km
Flattening: 0.0034

Rocket info:
Inertia Details

Rocket Mass: 21.525 kg (without motor)
Rocket Dry Mass: 29.589 kg (with unloaded motor)
Rocket Loaded Mass: 31.069 kg (with loaded motor)
Rocket Inertia (with unloaded motor) 11: 91.097 kg*m2
Rocket Inertia (with unloaded motor) 22: 91.097 kg*m2
Rocket Inertia (with unloaded motor) 33: 0.160 kg*m2
Rocket Inertia (with unloaded motor) 12: 0.000 kg*m2
Rocket Inertia (with unloaded motor) 13: 0.000 kg*m2
Rocket Inertia (with unloaded motor) 23: 0.000 kg*m2

Geometrical Parameters

Rocket Maximum Radius: 0.15 m
Rocket Frontal Area: 0.070686 m2

Rocket Distances
Rocket Center of Dry Mass - Center of Mass without Motor: 0.474 m
Rocket Center of Dry Mass - Nozzle Exit: 1.617 m
Rocket Center of Dry Mass - Center of Propellant Mass: 1.267 m
Rocket Center of Mass - Rocket Loaded Center of Mass: 0.060 m


Aerodynamics Lift Coefficient Derivatives

Nose Cone Lift Coefficient Derivative: 2.000/rad
Fins Lift Coefficient Derivative: 2.084/rad

Center of Pressure

Nose Cone Center of Pressure position: 0.227 m
Fins Center of Pressure position: 3.168 m

Stability

Center of Mass position (time=0): 1.835 m
Initial Static Margin (mach=0, time=0): -0.357 c
Final Static Margin (mach=0, time=burn_out): -0.156 c
Rocket Center of Mass (time=0) - Center of Pressure (mach=0): 0.107 m


Parachute Details

Parachute Drogue with a cd_s of 0.4378 m2
Ejection signal trigger: At Apogee
Ejection system refresh rate: 105.000 Hz
Time between ejection signal is triggered and the parachute is fully opened: 1.0 s


Parachute Details

Parachute Main with a cd_s of 16.0525 m2
Ejection signal trigger: 167.64 m (AGL)
Ejection system refresh rate: 105.000 Hz
Time between ejection signal is triggered and the parachute is fully opened: 1.0 s

Final Simulation Detail:
Initial Conditions

Position - x: 0.00 m | y: 0.00 m | z: 668.00 m
Velocity - Vx: 0.00 m/s | Vy: 0.00 m/s | Vz: 0.00 m/s
Attitude - e0: -0.009 | e1: -0.000 | e2: -0.000 | e3: -1.000
Euler Angles - Spin φ : -90.50° | Nutation θ: -0.00° | Precession ψ: -90.50°
Angular Velocity - ω1: 0.00 rad/s | ω2: 0.00 rad/s| ω3: 0.00 rad/s


Surface Wind Conditions

Frontal Surface Wind Speed: 2.19 m/s
Lateral Surface Wind Speed: 2.28 m/s


Launch Rail

Launch Rail Length: 5.2  m
Launch Rail Inclination: 90.00°
Launch Rail Heading: 181.00°


Rail Departure State

Rail Departure Time: 0.338 s
Rail Departure Velocity: 22.814 m/s
Rail Departure Stability Margin: -0.340 c
Rail Departure Angle of Attack: 7.932°
Rail Departure Thrust-Weight Ratio: 9.223
Rail Departure Reynolds Number: 4.079e+05


Burn out State

Burn out time: 3.900 s
Altitude at burn out: 538.815 m (AGL)
Rocket velocity at burn out: 223.937 m/s
Freestream velocity at burn out: 223.485 m/s
Mach Number at burn out: 0.647
Kinetic energy at burn out: 7.419e+05 J


Apogee State

Apogee Altitude: 2053.909 m (ASL) | 1385.909 m (AGL)
Apogee Time: 12.271 s
Apogee Freestream Speed: 39.353 m/s


Parachute Events

Drogue Ejection Triggered at: 12.276 s
Drogue Parachute Inflated at: 13.276 s
Drogue Parachute Inflated with Freestream Speed of: 32.995 m/s
Drogue Parachute Inflated at Height of: 1380.512 m (AGL)
Main Ejection Triggered at: 55.524 s
Main Parachute Inflated at: 56.524 s
Main Parachute Inflated with Freestream Speed of: 29.995 m/s
Main Parachute Inflated at Height of: 137.214 m (AGL)


Impact Conditions

X Impact: 856.142 m
Y Impact: -619.115 m
Latitude: -23.3691753°
Longitude: -48.0030065°
Time of Impact: 83.319 s
Velocity at Impact: -4.907 m/s


Stability Margin

Maximum Stability Margin: -0.056 c at 3.63 s
Minimum Stability Margin: -0.357 c at 0.00 s


Maximum Values

Maximum Speed: 231.924 m/s at 3.53 s
Maximum Mach Number: 0.670 Mach at 3.53 s
Maximum Reynolds Number: 3.978e+06 at 3.51 s
Maximum Dynamic Pressure: 2.813e+04 Pa at 3.53 s
Maximum Acceleration During Motor Burn: 81.364 m/s² at 0.59 s
Maximum Gs During Motor Burn: 8.297 g at 0.59 s
Maximum Acceleration After Motor Burn: 31.645 m/s² at 4.98 s
Maximum Gs After Motor Burn: 3.227 g at 4.98 s
Maximum Stability Margin: -0.056 c at 3.63 s
Maximum Upper Rail Button Normal Force: 0.111 N
Maximum Upper Rail Button Shear Force: 4.028 N
Maximum Lower Rail Button Normal Force: 0.163 N
Maximum Lower Rail Button Shear Force: 7.544 N


Numerical Integration Settings

Maximum Allowed Flight Time: 600.000000 s
Maximum Allowed Time Step: inf s
Minimum Allowed Time Step: 0.000000e+00 s
Relative Error Tolerance:  1e-06
Absolute Error Tolerance:  [0.001, 0.001, 0.001, 0.001, 0.001, 0.001, 1e-06, 1e-06, 1e-06, 1e-06, 0.001, 0.001, 0.001]
Allow Event Overshoot:  True
Terminate Simulation on Apogee:  False
Number of Time Steps Used:  282
Number of Derivative Functions Evaluation:  658
Average Function Evaluations per Time Step: 2.333333
