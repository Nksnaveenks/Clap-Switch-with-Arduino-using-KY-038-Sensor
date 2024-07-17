In this project we are going to make Clap switch circuit using the concept of ADC (Analog to Digital Conversion) in ARDUINO UNO. We are going to use a MIC and Uno to sense the sound and trigger a response. This Clap ON Clap OFF switch basically turns ON or OFF the device, by using the clap sound, as switch.
On clapping there will be a peak signal at the MIC which is much higher than normal, this signal is fed to the amplifier, though a High Pass Filter. This amplified voltage signal is fed to ADC, which converts this high voltage into a number. So there will be a peak in the ADC reading of the UNO. On this peak detection we will toggle an LED on the board, on each clap.
This project will be able to help people who are naturally born dumb and physically handicapped to be able to be able to use thier home automation without the help of others.


The sound sensor allows to detect when the sound has exceeded a set point . The sound or the
sensitivity is detected via a microphone which is already inbuilt in the sensor . The sensitivity level
can be adjusted via a potentiometer .
Relay is used in this circuit to control the current .It controls the high current using a low current
signal .
When the sensitivity exceeds the set point ,the bulb connected will turn on ,the output is sent low .
Once again if the sound exceeds ,the bulb is turned off and the output is sent high.


![image](https://github.com/Nksnaveenks/Clap-Switch-with-Arduino-using-KY-038-Sensor/assets/155534229/ceb5d369-4c36-4b09-82fe-15a358a4f984)


![image](https://github.com/Nksnaveenks/Clap-Switch-with-Arduino-using-KY-038-Sensor/assets/155534229/cd0d7a4a-f073-4b06-bb7d-26942866ab74)




