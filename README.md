# Non-Contact AC Voltage Detector

The **AC Voltage Detector** is a non-contact device designed to detect the presence of **AC voltage** in electrical wires and systems without physical contact.
It enhances **electrical safety** by alerting users through a **visual (LED)** and **audible (buzzer)** indication whenever AC voltage is detected.
This project is based on the principle of **electromagnetic induction**, where an alternating electric field around live wires is sensed and amplified using transistor-based circuitry.

---

## 🧠 Working Principle

* Live AC wires generate a **changing electromagnetic field**
* A sensing wire picks up this field
* The weak signal is amplified using **BC547 NPN transistors**
* Once the signal crosses a threshold:

  * **LED glows**
  * **Buzzer beeps**
* This alerts the user about the presence of AC voltage without direct contact

---

## 🔧 Components Used

| S.No | Component        | Specification    | Quantity    |
| ---- | ---------------- | ---------------- | ----------- |
| 1    | NPN Transistor   | BC547            | 3           |
| 2    | LED              | —                | 1           |
| 3    | Battery          | 9V               | 1           |
| 4    | Breadboard       | —                | 1           |
| 5    | Connecting Wires | —                | As required |
| 6    | Resistors        | 1MΩ, 100kΩ, 100Ω | Each 1      |
| 7    | Buzzer           | 5V               | 1           |

---

## 🔌 Circuit Description

* The sensing wire is connected to the **base of the first transistor**
* Signal is amplified through **three transistor stages**
* Final stage drives the **LED and buzzer**
* Powered using a **9V battery**
* Designed for **low cost and easy implementation**
  
---

## ✅ Result

* Successfully detects the presence of AC voltage
* Provides **clear visual and audio alerts**
* Works without physical contact with live wires
* Improves safety during electrical maintenance

---

## 🏭 Applications

* Electrical maintenance and repair
* Household safety checks
* Industrial electrical safety
* Testing and troubleshooting live circuits

