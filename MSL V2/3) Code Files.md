![[Rgb_PulseIn_005 1.ino]]

For Connections and board manager setup Refer :- [[1)Connections]] (use UNO setup)
- Upload Arduino as ISP Programmer First (**Do Not Insert Electrolytic 10uf,50v Cap on Gnd (-ve) and reset (+ve))**
- 
-  
- Select the Board (Arduino UNO)
- ![[Pasted image 20251013103351.png]]
- Select the Port COM* (Arduino Uno) - Connect the UNO with laptop - Confirm the port in device manager
- ![[Pasted image 20251013103512.png]]
- Setup the Arduino Uno As ISP in examples of any other saved program for ISP
- ![[Pasted image 20251013102658.png]]

- Verify and Upload the ISP Code to the UNO board.
- Disconnect the Uno from laptop and insert 10uf 50v electrolytic Capacitor +ve terminal to reset on UNO board and negative terminal of capacitor to GND.
- **Upload the RGB_Pulsein_005 code to ATtiny85 20PU (Now)**
	-Insert ATtiny85 IC on Bread Board and Make Connections As mentioned above 
	- ![[Pasted image 20250831132002.png]]
	- 













- Set the Board type :- ATtiny45/85(Optiboot)
- ![[Pasted image 20251013103052.png]]
- Select the COM port
- ![[Pasted image 20251013105057.png]]
- ![[Pasted image 20251013105123.png]]
- ![[Pasted image 20251013105201.png]]
- ![[Pasted image 20251013105222.png]]
- ![[Pasted image 20251013105258.png]]
- Ensure all this 
- ![[Pasted image 20251013105320.png]]
- Now Burn Bootloader
	- ![[Pasted image 20251013105349.png]]
	- Obverse the message done burning bootloader
	- Disconnect the UNO and Connections On Bread Board 
