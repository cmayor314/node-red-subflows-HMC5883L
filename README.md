# node-red-subflows-HMC5883L
Subflows to read information from the HMC5883L 3-axis digital compass via the I2C bus 

## Included Files:

All these subflows can be installed/used independently from each other.

**confirmHardwareIdentity.json** - to confirm the correct device exists on the I2C bus

**readConfigRegister.json** - Read the configuration register

**readStatusRegister.json** - Read the status register

**getCompassReading.json** - get 3D compass reading

**getCurrentOperationalModeStatus.json** - get the Current Operational Mode Status

![image](https://user-images.githubusercontent.com/105139648/173205894-018f3b0e-b335-48ee-b77a-c927139aa8fd.png)


## Additionally Required:

The node-red-contrib-i2c is **required** for this subflow.

https://flows.nodered.org/node/node-red-contrib-i2c

## Usage:

Send an arbitrary payload to the subflow, get results.

## Latest Datasheet: 

https://www.digikey.com/en/datasheets/honeywellmicroelectronicsprecisionsensors/honeywell-microelectronics-precision-sensors-hmc5883l

## Caveat emptor

This collection of subflows is not well documented. I made this flow years ago as a test, it worked fine, and then I didn't need to use that specific component anymore so I never went back and documented it well.  

I have uploaded it here so it doesn't disappear entirely, and somebody else could use it.  It works as advertised.

## Import what you need

![image](https://user-images.githubusercontent.com/105139648/173206816-921b08c8-c977-4b96-8937-e5889f365760.png)

