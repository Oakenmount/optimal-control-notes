


## Modeling dynamic systems

|Symbol|Family of Variables |
|--|--|
| p | Parameters |
| u | Controllable inputs |
| w | Uncontrollable inputs (disturbances) |
| x | Dynamic states |
| y | Process outputs |
| n | Measurement errors |
| z | Observations |

![Elements of the dynamic system](https://i.imgur.com/0DrXTYH.png)

*Open-loop control* - No path from **x** to **u** (Process is subjected to control inputs (**u**) without regard for state (**x**). Must be adequately "controllable".
*Closed-loop control* - Includes feedback information (i.e. through dynamic states **x**). Must be adequately "observable".
*Controllable* - If there is an independent natural path between every component in **x** and at least one element of **u**, the the process is likely completely controllable.
*Observable* - If there is an independent natural path between every component in **x** and at least one element of **y**, the the process is likely completely observeable.
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTAwOTM4NzQ2LC04NzU5NjY2ODksNzMwOT
k4MTE2XX0=
-->