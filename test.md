Next, connect GPIO Q0–Q9 to LEDs, and put a series resistor (e.g., 470 Ω) on each LED. This is because we need to limit the current reaching the LEDs. We can calculate the minimum resistance needed with the formula:

R = (V_supply − V_f) / I

where:
- V_supply = supply voltage (e.g., 5 V)
- V_f = LED forward voltage (e.g., ~2 V for red, ~3 V for blue/white)
- I = desired current (e.g., 5–15 mA)

Power‑limiting resistors prevent excessive current that could damage the LED or the driving IC. In practice, standard resistor values such as 220 Ω, 330 Ω, or 470 Ω are chosen depending on brightness and power budget: lower resistance gives more current (brighter), higher resistance gives less current (lower power, longer life).
