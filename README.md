# HomeSecurity.io
A keypad-based password door lock system together with buzzer alarm system provides home security if there is any unknown disturbance created.

Working Principle:

1. Once the circuit is powered, microcontroller sends commands to the LCD to display “enter password” on LCD.  Now we need to enter the password using the keypad. Once password is entered, it displays 5 stars on LCD to indicate that controller read password successfully.

2. Now the controller compares the entered password with predefined password. If the password is matched then controller makes P3.6 high and P3.7 low, so the motor driver gets the input signals for forward motion of the motor.    

3.  As a result, the Door motor rotates in forward direction to            open the door. After a delay of 10seconds, the microcontroller makes P3.6 low and P3.7 high, so the motor driver gets the input signals for reverse motion. As a result, the Door motor rotates in reverse direction to close the door.

4. If the password is not matched, then microcontroller maintains both P3.6 and P3.7 low. Hence, the door motor is stationary so that door    remains closed.

Advantages: 
1. Used for personal safe guarding of homes.
2. Can be used in vaults.
3. Can be used to protect the armed transport vehicles.

Application:
1. This simple circuit can be used at residential places to ensure better safety.
2. It can be used at organisations to ensure authorised access to highly secured places.
3. With a slight modification this Project can be used to control the switching of loads through password




