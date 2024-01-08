


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
*Controllable* - System is controllable at $t_0$ if there is a *control history*, **u**$(t)$, in time interval $[t_0, t_f]$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg3NTk2NjY4OSw3MzA5OTgxMTZdfQ==
-->