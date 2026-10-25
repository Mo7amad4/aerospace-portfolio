# Rocketry Terms I Learned (The Hard Way)

Written after my rocket went 2 centimeters in v1 and 213m in v3.

### The Dots
- **CG (Center of Gravity) - Blue Dot:** Where your rocket balances if you put it on your finger. This is where WEIGHT lives. Heavier nose = CG moves forward.
- **CP (Center of Pressure) - Red Dot:** Where AIR pushes on your rocket. Bigger fins = CP moves backward.
- **Stability (cal):** Distance between CG and CP, measured in "body tube diameters". 
    - Formula: (CP - CG) / diameter
    - < 1.0 = backflip and crash (my v1: -1.12)
    - 1.5 to 2.5 = Perfect
    - > 3.0 = Too stable, will point into wind (my v3: 3.61)

### The Motor - C6-5
- **Letter (C):** Total power. A=2.5Ns, B=5Ns, C=10Ns, D=20Ns... each letter = double power.
- **First Number (6):** Average thrust in Newtons. How hard it kicks.
- **Second Number (5):** Delay in seconds after motor burns out until ejection charge fires and pops the parachute.
- **P = Plugged:** No ejection at all. Your rocket becomes a lawn dart. 95 ft/s crash.

### Flight Stuff
- **Apogee:** Highest point your rocket reaches. Goal = high.
- **Velocity off rod:** Speed when it leaves the launch pad. Must be > 35 ft/s (10 m/s) or a gust of wind will tip it.
- **Ground Hit Velocity:** How fast it hits ground. With parachute: 12-15 ft/s = safe. Without: 95 ft/s = broken.
- **Total Impulse (Ns):** Motor's total energy. C6 = 10 Newton-seconds.

### OpenRocket Stuff
- **Override:** Manually setting mass/CG because you know better than the simulator. Dangerous if you get it wrong (I did).
- **Fin Flutter:** Fins wobble at high speed. Make them thicker.
- **Weathercocking:** Rocket turns into wind because it's too stable.

---
Built in OpenRocket 22.02, Estes motors database.
v1 = fail, v2 = fly, v3 = fly + land.