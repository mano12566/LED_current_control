   About the Project
This project is my second electrical engineering simulation. I used the Falstad Circuit Simulator to study resistor networks, focusing on how connecting resistors in series and parallel changes the total equivalent resistance ($R_{eq}$), current, and voltage distribution.

---

   Key Concepts
* **Series Connection:** Resistors are connected end-to-end, so the current stays the same across all components while the voltage splits ($R_{eq} = R_1 + R_2 + \dots$).
* **Parallel Connection:** Resistors share the same two nodes, so the voltage remains constant while the current splits across branches ($\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots$).

---

  What I Built & Tested
I designed and simulated 5 different circuits in Falstad to compare theoretical calculations with actual simulation values:

1. **Two Resistors in Series:** Verified that total resistance increases ($300\,\Omega$) and voltage divides across resistors.
2. **Three Resistors in Series:** Observed a further decrease in total current as overall resistance increased ($600\,\Omega$).
3. **Two Resistors in Parallel:** Confirmed that total resistance drops ($66.67\,\Omega$) below the value of the smallest individual resistor.
4. **Three Resistors in Parallel:** Measured an increased overall circuit current as resistance dropped further ($54.55\,\Omega$).
5. **Combination Circuit (Series-Parallel):** Applied $R_{eq}$ rules to solve a mixed circuit with both series and parallel branches ($220\,\Omega$).

---

  What I Learned
* How series and parallel configurations directly impact total current and voltage sharing.
* How to calculate and verify equivalent resistance for both simple and combination circuits.
* Practice using Falstad to simulate circuit networks and analyze practical values against theory.
