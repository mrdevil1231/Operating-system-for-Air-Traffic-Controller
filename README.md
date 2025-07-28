# Operating-system-for-Air-Traffic-Controller
This projects aims to simulate air traffic control system using tools from C standard library. 

To run the program all files must be present in same root folder.

**Instruction for running the programme files**
1. It is recommended to run the programs on LINUX Terminal for better understanding of working of OS.
2. Each instance of _plane.c_ represent a airplane with necessary details required from users. The process will not terminate unless it gets termination request from _airtrafficcontroller.c_.
3. Similarly _airport.c_ represent each unique airport identified by their airport No.  
4. There can be multiple instances for plane.c and airport.c
5. cleanup.c is backround process which holds termination request from user to terminate all programm currently running.
6. _airtrafficcontroller.c_ is also a backround process which handles coordination and communication between plane.c, cleanup.c and airport.c.
