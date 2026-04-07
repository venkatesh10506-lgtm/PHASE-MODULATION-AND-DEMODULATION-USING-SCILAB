# PHASE-MODULATION-AND-DEMODULATION-USING-SCILAB
AIM

To write a program for Phase Modulation and Demodulation using SCILAB and to observe and measure the phase deviation and modulation index.

APPARATUS REQUIRED

Computer with i3 Processor or higher
SCILAB Software

THEORY

Phase Modulation (PM) is a modulation technique in which the phase of the carrier signal is varied in accordance with the instantaneous amplitude of the modulating signal, while the amplitude of the carrier remains constant.

Phase Deviation (Δφ)

Phase deviation represents the maximum change in phase of the carrier signal.

Δφ = kp * Am

Where:

kp = Phase sensitivity (rad/volt)
Am = Amplitude of modulating signal
Modulation Index (mp)
mp = Δφ

For sinusoidal signals:

mp = kp * Am
PM Signal Equation
s(t) = Ac cos(2πfc t + kp m(t))

For sinusoidal modulating signal:

s(t) = Ac cos(2πfc t + mp sin(2πfm t))

Where:

Ac = Carrier amplitude
fc = Carrier frequency
fm = Modulating frequency
kp = Phase sensitivity
mp = Modulation index

ALGORITHM

Define parameters:
Sampling frequency Fs
Time duration T
Carrier frequency fc
Modulating frequency fm
Phase sensitivity kp
Generate signals:
m(t) = sin(2πfm t)
c(t) = cos(2πfc t)
PM Modulation:
s(t) = cos(2πfc t + kp * m(t))
PM Demodulation:
Differentiate the PM signal
Apply envelope detection:
|s(t)|
Use low-pass filter to recover the original signal
Plot all signals:
Modulating signal
Carrier signal
PM signal
Demodulated signal

PROCEDURE

Refer to the algorithm and write the SCILAB code.
Open SCILAB software.
Create a new script file.
Enter the program and save it.
Execute the code.
Debug errors if any and re-run.
Observe the generated waveforms.


TABULATIONS

![WhatsApp Image 2026-04-07 at 1 05 31 PM](https://github.com/user-attachments/assets/4f6f6c8a-7f81-457e-a497-bca4998b70f4)

OUTPUT GRAPH :

![WhatsApp Image 2026-04-07 at 1 05 31 PM (1)](https://github.com/user-attachments/assets/0c74f1fd-16a3-4260-a195-fb97fa8d8860)

<img width="761" height="537" alt="image" src="https://github.com/user-attachments/assets/c720857c-0d95-45f4-8da6-2bf512582ec7" />


RESULT

![WhatsApp Image 2026-04-07 at 1 05 31 PM (2)](https://github.com/user-attachments/assets/cfd500b0-33ea-4f8d-9d34-09d09fddc501)
