# KWM-Bose
Repo for BostonHack 2019 Bose AR spatial awareness and hands-free, voice-free control idea

#### Josh Wade, Spencer Kelly, Dan Molyneaux

KWM Bose is an Android application created using Android studio and Bose AR SDK. The application is intented for bluetooth integradion with Bose's AR compatible devices (Bose Frames, Bose Headphones 700 and QC35 headphones II.) When started, the application will prompt the user to connect to a Bose bluetooth device, once connected, the orientation of the device is used to control volume.

In awareness mode, a quick look left or right will lower the volume and turning back forward will return it to its original volume. This is intented to improve safety and spacial awareness for the user and to make the process of pausing music listening to talk to someone while working more seemless. Awareness mode can be toggled on and off by the user.

Tilting your head to either side will raise or lower the android device volume. 



### Reference:
	https://bosedevs.gitbook.io/bose-ar-android-workshop/
	
### Sensors:
	Accelerometer
	Gyroscope
	magnetometer

	Rotation:
	-Measures the orientation of the device relative to magnetic north
	-Uses the accelerometer, gyroscope, and magnetometer to derive the orientation value
	-Provides 4-dimension quaternion values
	-Quaternions emitted by the SDK are unit quaternions with a norm of 1
	-Unitless
	

