# TP4056 Reverse Battery Protection
Unfortunately the DW01A IC does not support battery reversal, perhaps adding a 2N7002 Transistor to the board will solve the problem.

TP4056 + Protection:

![img](https://raw.githubusercontent.com/rtek1000/TP4056_Reverse_Battery_Protection/refs/heads/main/TP4056_Prot_Reverse_Red_Note.png)

2N7002:

![img](https://raw.githubusercontent.com/rtek1000/TP4056_Reverse_Battery_Protection/refs/heads/main/2N7002_Page1.png)

Note: This configuration was experimented with in this [project](https://github.com/rtek1000/Datalogger_2039).


-----

Note: Leaving the battery charging with the TP4056 for long periods or indefinitely can reduce battery life. If, after charging, a current of 40 mA is being delivered to the battery, some datasheets report Ibat = 40 mA for Vfloat.

> The question is asked, “Should I disconnect my laptop from the power grid when not in use?” Under normal circumstances this should not be necessary because charging stops when the Li-ion battery is full. A topping charge is only applied when the battery voltage drops to a certain level. Most users do not remove the AC power, and this practice is safe.

https://batteryuniversity.com/article/bu-808-how-to-prolong-lithium-based-batteries

-----

##### Hardware:

Released under CERN OHL 1.2: https://ohwr.org/cernohl

Note: This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE
