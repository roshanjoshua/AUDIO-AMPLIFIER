# AUDIO-AMPLIFIER
The Audio Amplifier is an Electronic Device which convert the Audio input Sound to an Amplified signal of the Speaker. Our Circuit uses the amplifier IC LA4440 to Amplify the sound. The input is given to circuit using an Aux cable from the phone.

The First part of the circuit consists of a bridge rectifier circuit which has four silicon diodes 1N4007. It rectifies the input 12V AC from a Transformer. The rectified voltage is then filtered using a 1000 micro farad capacitor. Then a Voltage regulator is used which provides constant 12V DC supply to the Circuit.

<img width="700" height="620" alt="image" src="https://github.com/user-attachments/assets/db89f797-ef31-4cae-ae7d-56070e27a0c1" />


The above shown diagram is that of the internal circuit of the LA4440 IC with the audio input at pin 2. It is an Op-Amp circuit which multiplies the signal each time by a gain value until it reaches the output at pin 12. Pins 3, 6, 8, 14 are grounded because the second Op-Amp input circuit is not needed as there is only one signal. 4th pin is not connected as it is for the mute button. Pins 9 and 13 are Surge Protectors, 1 and 7 are negative feedbacks. A potentiometer is incorporated to control the volume. 6 Filters are used to improve Sound Quality.

<img width="875" height="645" alt="image" src="https://github.com/user-attachments/assets/594e664a-4909-455b-8121-17c9528a90ad" />

