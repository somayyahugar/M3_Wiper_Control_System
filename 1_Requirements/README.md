# Highlevel Requirements and Lowlevel Requirements
##  Highlevel Requirements

| HLR_ID  | Description |
| ------------- | ------------- |
| HLR_1  | The Red LED is on to indicate the ignition Key position at ACC  |
| HLR_2  | LEDs come on in desired pattern at set frequency replicating speed control of wiper arm  |
| HLR_3 | The Red LED is off to indicate the Ignition Key position at Lock |

##  Lowlevel Requirements

| HLR_ID  | LLR_ID | Description |
| --- | ----- | ------------- |
|   | LLR_1 | LEDs come on in desired pattern at set frequency at 1 Hz(Low Speed)     |
| HLR_2  | LLR_2 | LEDs come on in desired pattern at set frequency at 4 Hz(Medium Speed)   |
| | LLR_3 | LEDs come on in desired pattern at set frequency at 8 Hz(High Speed) |

##  SWOT Analysis

######  Strenght

* No manual or human intervention needed.

* 3 modes of speed control available.

* It reduces the occurrences of accidents due to distractions.

* The wiper arm return backs to its original position, when turned off.

######  Weaknesses

* Differences between the button presses corresponding to the Iglition on and speed control is not clearly specified.
*  The controller design is not flexible with additional integration features.

######  Opportunities

* By utilizing the input capture mode of timer, the differentiation between button presses can be achieved.
* Complete end to end solution can be obtained by working on integration problems.

######  Threats

* The developed system is not waterproof, fireproof, etc..
* Sensor module unit or Motor control unit functionality cannot be validated beforehand.
