Next, connect GPIO Q0–Q9 to LEDs, and connect their GND to one resistor with the value of 470 Ω. This is because we need to limit the current reaching the LEDs. We can calculate the minimum resistance needed with the formula:



\[
R = \frac{V_{\text{supply}} - V_f}{I}
\]



where:

- \(V_{\text{supply}}\) = supply voltage (e.g., 5 V)  
- \(V_f\) = LED forward voltage (depends on color, ~2 V for red, ~3 V for blue/white)  
- \(I\) = desired current (typically 10–20 mA for standard LEDs)  

Power‑limiting resistors are generally used to prevent excessive current that could damage the LED or the driving IC. In practice, standard resistor values such as **220 Ω, 330 Ω, or 470 Ω** are chosen depending on the brightness required and the power budget. A lower resistance allows more current and brighter LEDs, while a higher resistance reduces current, conserves power, and extends component life.
