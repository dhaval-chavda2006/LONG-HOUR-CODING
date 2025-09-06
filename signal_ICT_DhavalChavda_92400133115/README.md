##Signal Generation and Operations Package
---Project Overview

This project is a custom Python package named signal_ICT_DhavalChavda_92400133115 developed as part of the Programming with Python Long Hour Coding Exam at Marwadi University.

The package demonstrates concepts of Signals and Systems by implementations for:

Unitary signals (unit step, unit impulse, ramp)
Trigonometric signals (sine, cosine, exponential)
Basic signal operations (time shifting, time scaling, addition, multiplication)


------Modules Overview--------

1. unitary_signals.py

Contains functions for generating basic discrete signals:

unit_step(n) → Generates a unit step signal.
unit_impulse(n) → Generates a unit impulse signal.
ramp_signal(n) → Generates a ramp signal.

2. trigonometric_signals.py

Provides functions for continuous signal generation:

sine_wave(A, f, phi, t) → Generates a sine wave.
cosine_wave(A, f, phi, t) → Generates a cosine wave.
exponential_signal(A, a, t) → Generates an exponential signal.

3. operations.py

Implements basic signal operations:

time_shift(signal, k) → Shifts the signal in time by k units.
time_scale(signal, k) → Scales the time axis of the signal.
signal_addition(signal1, signal2) → Adds two signals.
signal_multiplication(signal1, signal2) → Multiplies two signals point-wise


Outputs:===

The package generates and plots:

Unit step, impulse, and ramp signals.
Sine and cosine waves.
Time-shifted sine waves.
Added unit step and ramp signals.
Multiplied sine and cosine signals.