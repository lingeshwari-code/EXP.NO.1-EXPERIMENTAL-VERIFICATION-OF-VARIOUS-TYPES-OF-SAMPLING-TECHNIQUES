# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

## AIM
 1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## APPARATUS REQUIRED
 Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
### Natural Sampling
1. Refer to the block diagram and carry out the following connections and switch setting.
2. Connect power supply in proper polarity to the kit DCL-10 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer.
4. and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the 
connecting chords provided.
5. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
6. Using clock selector switch (S1) select 8khz sampling frequency.
7. Using switch (Sw2) select 50% duty cycle.
8. Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
9. Repeat the procedure for the 2khz sine wave signal as input.

### FLAT TOP SAMPLING: 
1. Refer to the block diagram and carry out the following connection and switch setting.
2. Connect power supply in proper polarity to the kit DCL-01 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the 
connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
5. Using clock selector switch(S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle. 
Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low
pass Butterworth filter and take necessary observation as mentioned below. 
7. Repeat the procedure for the 2khz, sine wave signal as input
## CIRCUIT DIAGRAM
![image](https://github.com/user-attachments/assets/7e2919ef-428b-4566-89bd-222e9826afec)

## MODEL GRAPH
![image](https://github.com/user-attachments/assets/65dc4597-8c81-4adf-8837-5a2d111d065f)

## Table
![Screenshot 2025-04-13 at 22 42 46_4606e559](https://github.com/user-attachments/assets/e085b43c-8c6f-4e54-8067-212d0d4c0e62)

## Output
![Screenshot 2025-04-13 at 22 41 05_d857e723](https://github.com/user-attachments/assets/63f0b7ff-4a92-4fd1-91bb-efaeb3561c1e)
![Screenshot 2025-04-13 at 22 42 02_9fcae4a7](https://github.com/user-attachments/assets/f79d4b1b-47d7-4773-8854-3d52f0942810)

## Result
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques was verified successfully.


