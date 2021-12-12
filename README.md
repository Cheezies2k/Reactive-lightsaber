# Reactive-lightsaber
A lightsaber made using a raspberry pi zero, many leds and distance sensors.

The end product will be a lightsaber that reacts to swinging and hitting by playing sounds. It will be able to change colours and sounds too with the press of a button. The most unique part of it will be the eight laser distance sensors around the rim of it that detect if and where anything hits the lightsaber. This information will be able to be relayed to the pi zero and then displayed as a bright flash/light at the exact positon of the object on the leds.

The lightsaber is currently being controlled by a pi pico, but due to unstability with multithreading and speed limitations, it is being upgraded to a pi zero so that audio and leds are able to function at the same time without interferance

All of the parts have been 3D printed and are press fit onto a chrome coated tube that runs all through the middle og the saber, giving it more strength and stability. Around the outside of the leds there is a polycarbonte tube protecting them from hits. Right now, the tube is only made blurry with spray on glass frosting but it chips off when it is hit so a better solution might be needed. Although its fine for now.

The rest of the issues and possible solutions are found in the "Current issues and possible solutions" file.
