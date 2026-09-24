# Generation-and-detection-of-AM-using-SCILAB---T1---M4---ODD
# AIM

To generate and detect the amplitude modulation and demodulation using SCILAB and to calculate modulation index of AM.

# EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

# THEORY

Modulation can be defined as the process by which the characteristics of carrier wave are varied in accordance with the modulating wave (signal). Modulation is performed in a transmitter by a circuit called a modulator.

Need for modulation is as follows:

* Avoid mixing of signals
* Reduction in antenna height
* Long distance communication
* Multiplexing
* Improve the quality of reception
* Ease of radiation

Amplitude Modulation is the process of changing the amplitude of a relatively high frequency carrier signal in proportion with the instantaneous value of the modulating signal. The output waveform contains all the frequencies that make up the AM signal and is used to transport the information through the system. Therefore the shape of the modulated wave is called the AM envelope. With no modulating signal the output waveform is simply the carrier signal. Coefficient of modulation is a term used to describe the amount of amplitude change present in an AM waveform. There are three degrees of modulation available based on value of modulation index.

1. **Under modulation:** `m < 1`, `Em < Ec`
2. **Critical modulation:** `m = 1`, `Em = Ec`
3. **Over modulation:** `m > 1`, `Em > Ec`

**Note:** Keep all the switch faults in off position.

# ALGORITHM

### 1. Define Parameters

First, define the parameters for your signals:

* Carrier frequency (fc)
* Modulating signal frequency (fm)
* Sampling frequency (Fs)
* Duration of the signal (T)

### 2. Create Time Vector

Create a time vector based on the sampling frequency and duration.

### 3. Create Modulating Signal

Define the modulating signal (message signal).

### 4. Create Carrier Signal

Define the carrier signal.

### 5. Perform Amplitude Modulation

Multiply the carrier signal by the modulating signal plus 1 (to ensure the modulation depth).

### 6. Plot the Signals

Visualize the modulating, carrier, and modulated signals.

### 7. Demodulate the AM Signal

To demodulate, you can use envelope detection. One way is to rectify the signal and then apply a low-pass filter.

### 8. Plot the Demodulated Signal

Visualize the demodulated signal.

### 9. Compare Signals

Compare the original modulating signal with the demodulated signal.

# PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

# TABULATION

<img width="1600" height="994" alt="image" src="https://github.com/user-attachments/assets/da00ad3d-3412-4032-ad79-23e6c2fbbc9b" />

# CALCULATION

1. **ma (Theory) = am/ac =*4

2. **ma (Practical) = (Emax - Emin) / (Emax + Emin) =8

# CODING 
<img width="1306" height="1600" alt="image" src="https://github.com/user-attachments/assets/83ef7d5e-f563-4db3-b907-777bfd41ae4f" />

# GRAPH
<img width="1566" height="875" alt="image" src="https://github.com/user-attachments/assets/3dd91951-2bfd-4334-9080-5bc6887f492e" />

# RESULT 
<img width="1600" height="620" alt="image" src="https://github.com/user-attachments/assets/7265c5c3-653b-4b0c-82a6-d82b897fdbe2" />

# MARK ALLOCATION 
<img width="1600" height="916" alt="image" src="https://github.com/user-attachments/assets/6e3e8a15-d375-43bd-bae0-012c98c211f5" />






