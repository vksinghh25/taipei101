# Taipei 101 Damper Lab

A single-page interactive demo of the 660-tonne tuned mass damper near the top of Taipei 101.

Two identical towers face the same simulated wind: one with the pendulum locked, one with it free to swing. You can change wind speed and gustiness, try presets (everyday breeze, winter monsoon, Typhoon Soudelor 2015, resonance lock-in, mistuned damper), retune the pendulum and its hydraulic damping, and watch the live sway trace and the frequency-response curve.

Open `index.html` in a browser. There is no build step and there are no dependencies.

The physics is a simplified two-mass model (tower first mode at 6.8 s plus the pendulum) driven by random gusts and vortex shedding. It shows how the damper behaves; it is not engineering data for the real building.
