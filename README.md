# Reactive-lightsaber
A lightsaber made using a raspberry pi zero, many leds and distance sensors.

The end product will be a lightsaber that reacts to swinging and hitting by playing sounds. It will be able to change colours and sounds too with the press of a button. The most unique part of it will be the eight laser distance sensors around the rim of it that detect if and where anything hits the lightsaber. This information will be able to be relayed to the pi zero and then displayed as a bright flash/light at the exact positon of the object on the leds.

All of the parts have been 3D printed and are press fit onto a chrome coated tube that runs all through the middle og the saber, giving it more strength and stability. Around the outside of the leds there is a polycarbonte tube protecting them from hits. Right now, the tube is only made blurry with spray on glass frosting but it chips off when it is hit so a better solution might be needed. Although its fine for now.

The rest of the issues and possible solutions are found in the "Current issues and possible solutions" file.

After the completion of this saber, I am planning on making a second better version that this time includes:
	Only 4 distance sensors
	
	4 more dense led strips
	
	A secondary power source for better audio quality
	
	A teensy 4.1 instead of Rpi Zero
	
	4 Lipo batteries with a buck converter that regulates the power from 7.4V @ 5200 mA to 5V @ 6000 mA
	
	Extended battery life
	
	Teensy 4.1 turns itself and all other circutry off when shut down intead of going into sleep mode
	
	Foam and diffusion sheet on inside for better diffusion
	
	More space between leds and tube for better diffusion
	
	Gyroscope and Accelerometer with i2c communication
	
	Low pass filter for reducing audio noise
	
	EEPROM for storing last used colour while powered off
	
	Higher led brightness
	
