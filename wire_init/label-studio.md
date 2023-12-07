
How to use - do basic things like installing python and signing-up to label-studio.

then ;
- pip install label-studio
- label-studio start
- create a project and start labeling data (in the label studio UI in your browser)

what kind of sensor data we are dealing with, its a chew cycle 
How the sensor data looks like for left and right side to detect movements of the jaw
![[Pasted image 20231205114946.png]]


How many phases are there in a single chew cycle of the jaw

To spot these phases in accelerometer sensor data, you would need to analyze the patterns and changes in the signal :

1. Resting Phase: Look for periods of minimal variation or low amplitude in the accelerometer data.

2. Closing Phase: Observe a gradual increase in values as the jaw begins to close. This could manifest as an upward trend in the data.

3. Biting Phase: Identify cyclic patterns in the data with alternating peaks and troughs. The frequency of these cycles may correspond to the chewing rate.

4. Opening Again Phase: Look for a decrease in values as the jaw opens again after each bite.
