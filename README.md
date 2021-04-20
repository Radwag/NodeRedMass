# Radwag-mass
Node-red 

![Alt text](/en_header.png)

Radwag-mass node enables obtaining mass result from Radwag devices via TCP connection.

Package available :

https://www.npmjs.com/package/radwag-mass

![Alt text](/flow.png)


![Alt text](/payload.png)

The payload description :

	mass: The net value of mass
	unit: Current unit
	tare: The tare value
	stab: Determines stability
	zero: Determines if mass is in zero range
	range: Describes current range - mostly important when scale is multi-range
	digit: Determines count of highlighted digits when scale is legalized
	hidden: Determines count of hidden digits when scale is legalized
	

For more information and detailed instruction refer to:
http://filecloud.radwag.com/index.php/s/XGj1JvM7m9704nA
