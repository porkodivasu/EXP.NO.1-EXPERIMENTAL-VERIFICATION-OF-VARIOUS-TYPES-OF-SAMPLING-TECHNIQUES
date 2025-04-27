# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
Natural Sampling
Refer to the block diagram and carry out the following connections and switch setting.
Connect power supply in proper polarity to the kit DCL-10 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer.
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
Using clock selector switch (S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle.
Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
Repeat the procedure for the 2khz sine wave signal as input.
FLAT TOP SAMPLING:
Refer to the block diagram and carry out the following connection and switch setting.
Connect power supply in proper polarity to the kit DCL-01 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
Using clock selector switch(S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.
Repeat the procedure for the 2khz, sine wave signal as input
## CIRCUIT DIAGRAM
![Screenshot (72)](https://github.com/user-attachments/assets/42b1b59e-cc3b-4b0f-bb7d-2beec4feb663)
![Screenshot (71)](https://github.com/user-attachments/assets/c15f7620-1984-4fc1-8e50-b56d379cc8a5)


## MODEL GRAPH
![Screenshot (70)](https://github.com/user-attachments/assets/c9362ad3-6126-4273-bcaf-2ad250c8dd3b)
![Screenshot (69)](https://github.com/user-attachments/assets/04f7c40f-307b-4c9f-abc3-8759005ae2d7)

## TABLE
![Screenshot (89)](https://github.com/user-attachments/assets/5cba1e9a-8334-4c2d-9988-37ca04436995)

## OUTPUT GRAPHS
NATURAL SAMPLING:
![WhatsApp Image 2025-04-21 at 7 32 21 PM](https://github.com/user-attachments/assets/a47becd6-372a-4533-aaca-06d66b3d43c6)

FLAT TOP:
![WhatsApp Image 2025-04-27 at 8 05 09 PM](https://github.com/user-attachments/assets/b4ad664a-1814-43a8-ac46-e371dc032da2)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
