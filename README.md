# Walkthrough
This write-up details a method for remotely triggering an electric water gun using an RC car controller. The approach is to bypass the electric gun trigger mechanism and solder it to the RC car transmitter, in this case it was the “forward” command from the controller. When the forward command input is given to the receiver, this will complete the circuit and make the electric water gun “activate”.



Equipment Needed:


•	1x: Electrically powered water gun (I used the gun attached below via AliExpress)
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Screenshot%202024-11-01%20143343.png?raw=true)

•	1x: Remote Control car (I used the car attached below via Amazon)
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Screenshot%202024-11-01%20143438.png?raw=true)

•	1x: Philips head screwdriver


•	1x: Soldering iron


•	1x: Scissors


•	1x: Heat gun (optional)


Step 0


•	Make sure that both the RC car and the electric water gun operate as intended before disassembly. This is to ensure that any components are not faulty during troubleshooting when required


•	Fully charge the lithium battery included with the electric water gun



Step 1
•	Unscrew the RC car shell via Philips screwdriver
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Opened%20Car.png)


•	Identify what each wire connects to without disconnecting any wires
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/RC%20Receiver.png)


•	Based on the information given on the board, descriptions for each wire are as follows:


    o	Yellow: Back motion

    
    o	Blue: Forward motion

    
    o	Black: Negative Voltage

    
    o	Top White: Receiver Antenna

    
    o	Bottom White: Turn left

    
    o	Green: Turn Right

    
    o	Red: Positive Voltage


Step 2
•	Remove the motors and receiver from RC car shell


•	For this walkthrough, we will use the “forward” motion on the RC car to talk to the electric water gun


o	Cut the blue wire (representing “forward”) from the RC motor
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Receiver%20forward%20Wire.png)

Step 3
•	Cut the black and red wires connecting the RC car batteries to the receiver


Step 4
•	Disassemble the electric water gun via Philips screwdriver


•	Identify each wire on the water gun 


•	Circled on the top left are the positive and negative voltages that connect to the battery (included in the water gun box)


•	Circled on the right is the trigger that when pushed, tells the gun to fire the water 


o	Therefore, this means that a simple completion of the circuit is needed in order for the gun to operate

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Water%20Gun%20Disassembly.png)

•	Below is another angle of the water gun. The button for the trigger is circled

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Water%20Gun%20Disassembly%202.png)

Step 5
•	Cut both the black and red wires connecting the water gun to the battery connector (black plastic piece)

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/water%20Gun%20Power.png)

Step 6
•	Cut the black and red wires on the water gun battery 
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Water%20Gun%20Battery.png)

Step 7
•	Cut both the red wires on the water gun that acts as the trigger
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Water%20Gun%20Disassembly%202.png)

Step 8
•	Solder the black cable (negative voltage) on the RC car receiver to both the black cable on the water gun and the black cable on the included battery

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Negative%20Voltage%20Solder.png)

Step 9
•	Solder the red (positive voltage) on the water gun to the blue “forward” cable on the RC car receiver
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Forward%20and%20Positive%20Voltage%20Solder.png)


At this point the electric water gun should be able to fire when the “forward” command on the RC car is sent to the receiver. If not, verify your connections.


Step 10
•	Now that you have verified that the forward motion command works with electric water gun, cut the remaining 3 wires on the receiver excluding the white Antenna wire


o	Yellow: Back motion


o	White: Left motion


o	Green: Right motion

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Remove%20extra%20wiring.png)

Step 11
•	Insulate the newly soldered wire (optional)


•	Reassemble the electric water gun


o	Note: Personal choice for how to put the receiver and battery back into the electric water gun. I put the receiver in the gun and lazily taped the battery to the side with the antenna

![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Assembled%20Water%20Gun.png)

Now you should have an electric water gun that can fire wirelessly
![image alt](https://github.com/dakota033/Wireless-Electric-Water-Gun/blob/main/Final%20Product.png)
