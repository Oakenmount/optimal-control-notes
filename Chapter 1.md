


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

*Observable* - If there is an independent natural path between every component in **x** and at least one element of **y**, the the process is likely completely observable.

Dynamic system is often only partially observable and controllable, and may be sufficient for optimal control. 
Dynamic system may be divided into subprocesses.

*Stable* - If an uncontrollable subprocess in an otherwise controllable process does not cause the process to diverge, then it is *stable*. (Bounded inputs or conditions produce bounded response).

*Detectable* - If an unobserved subprocess is stable, the otherwise observable process is *detectable*. (Bounds on observed states can be estimated).

*Superposition characteristic* - The net response caused by two or more stimuli is the sum of the responses that would have been caused by each stimulus individually. E.g, if input _A_ produces response _X_ and input _B_ produces response _Y_ then input (_A_ + _B_) produces response (_X_ + _Y_)

$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI1MDAzNTg0MCwtMzExMDg0MTI0LDc2Mj
UwNzQ0NiwtNDQzMDA3MDQwLDE4MjM0NDY4NDEsLTg3NTk2NjY4
OSw3MzA5OTgxMTZdfQ==
-->