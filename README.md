# voltage-requlator

what is voltage requlator ?

Voltage regulator is a device that maintains a constant dc output

why do we use it in Robotics?

Voltage regulator boards are used to regulate and lower the higher voltages provided from unregulated sources. In robotics the regulated and lowered voltage levels are generally 5V or 3,3V logic voltage levels.

Voltage regulators make sure that the supply voltage doesn't vary too much about a certain mean and maintains a constant value.

for example : The IR sensor will require a constant voltage to perform efficiently and accurately over a long period of time. However the most likely application is when some IR sensors require more current than the arduino or any other programming board can provide. In such cases you will opt for external power supply which may exceed the rated voltage of the IR or the motors involved. In such cases to prevent damage to your sensors and motors you use a voltage regulator of lower value as required for the components to give in the correct specified voltage input.
