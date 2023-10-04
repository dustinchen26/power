# [bbuiolog] SNR, RSSI actual value Calculator
● online tool : https://dustinchen26.github.io/power

## Example
```
[bbuiolog] SNR, RSSI actual value Calculator
Author: Dustin_Chen, email: Dustin_Chen@compal.com or chuhpsdustin@gmail.com

SNR Calculation
1. [CRC.ind] Effective SNR: 159 => Calculate Actual SNR(dB): 15.5
2. [RX_ULSCH.ind] UL_CQI: 159 => Calculate Actual SNR(dB): 15.5
3. [HARQ.ind] PUCCH SINR: 159  => Calculate Actual SINR(dB): 15.5

RSSI Calculation
4. [RACH.ind] Per resource RSSI: 68  => Calculate Actual RSSI(dBFS): -93.5
5. [CRC.ind] RSSI: 42  => Calculate Actual RSSI(dBFS): -106.5
6. [HARQ.ind] PUCCH RSSI: 97  => Calculate Actual RSSI(dBFS): -79
7. [CRC.ind] Received Noise and Interference Power: 66  => Calculate Actual Received Noise and Interference Power(dBFS): -94.5
======================================================================================
(Note)
	actual SNR(dB) = Effective SNR * 0.5 - 64
	actual SNR(dB) = UL_CQI * 0.5 - 64
	actual SINR (dB) = Effective SNR * 0.5 - 64
	
	actual RSSI (dBFS) = RSSI * 0.5 - 127.5
	actual RSSI (dBFS) = Per resource RSSI * 0.5 - 127.5
	actual RSSI (dBFS) = PUCCH RSSI * 0.5 - 127.5
	actual Received Noise and Interference Power (dBFS) = IE *0.5 - 127.5
======================================================================================
```