# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

Tabulation:
![ce0530a0-27b3-416b-83f6-d3c4d2b011c8](https://github.com/user-attachments/assets/b4adfc12-9fcc-4146-b38b-f5558d691223)



__Output_:
<img width="1048" height="813" alt="521915989-359acc82-1ce6-4cd5-8c72-6b17c16175b3" src="https://github.com/user-attachments/assets/b7a0b224-7e3d-4ef0-b163-a6ac689a88e6" />
<img width="974" height="606" alt="521916108-421fe811-2db0-4ccc-8934-1e38c23d19fb" src="https://github.com/user-attachments/assets/77938729-eb4b-4b1c-8748-2ab0a766fccc" />
<img width="987" height="690" alt="521916224-f9978854-5a5d-47f9-95c9-d5f5dcb8ed27" src="https://github.com/user-attachments/assets/f810b70f-ec2b-4989-88e1-11ab77b43cf9" />


__Result__:
Thus the frequency division multiplexing is verified using python successfully.
