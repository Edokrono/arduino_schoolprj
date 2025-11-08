# arduino_schoolprj
Follows a taped track and stops/avoids obstacles using an HC-SR04 sensor and an L298N motor driver.
A small project made in first year of high school, i was with the 12th grade peers helping them and learning CS as i could. Very fun project!
I took some old files that i still have and port them into this Repo to show.

I translated the main readMe file in english:

*How it works:* Reads distance; if < **15 cm** → stop. Otherwise corrects motor speed to stay on path (simple threshold + correction).
- Control loop: threshold + small trim (note if you used PID or hysteresis).

**Results (track ≈12 m, 2 turns):**
- **9/10** successful runs
- **~38 s** average lap
- Safe stop at **≤15 cm**



*Team & my role:* Team of 3; I wrote sensor & motor control and did calibration with my older peers.
**Run it:** Open `.ino` in Arduino IDE, set TRIG/ECHO pins, upload.


