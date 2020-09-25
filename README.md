# Elevator control
Language: Java
This program simulates the control of a vertical passenger elevator (lift). The simulation is supposed to react to inputs made by a user
-   The lift does not have a door control
-   The lift waits at least 3 seconds when it reaches a destination floor
-   The number of floors must be queried when the program is started.One number for the lowest and one for the highest floor is requested. You can also enter negative numbers.  The maximum floor number is 12, the minimum -3.
-   The travel time between two consecutive floors is always 1 second
-   The elevator outputs each time it reaches a certain floor as destination ("X. Floor: Get off
-   please") or drives past it ("X. floor”)
-   When the lift has reached a certain floor as end position, the user can make requests for the next destinations
-   Several different destinations can be entered, up to a maximum of 4 destinations. No entries are counted for the current floor, these should not be accepted.
-   The completion of user input should be signalled by entering the number 99.
-   Only when all targets have been processed, new requests should be accepted again.
