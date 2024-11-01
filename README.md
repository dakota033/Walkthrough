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
![image alt](
