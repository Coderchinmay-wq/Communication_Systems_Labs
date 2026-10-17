# Experiment 02 – Amplitude Modulation and Demodulation

## Aim

To study the function of Amplitude Modulation and Demodulation
and to calculate the modulation index.

---

## Objectives

- Generate an Amplitude Modulated (AM) signal.
- Observe the AM waveform using an oscilloscope.
- Measure maximum and minimum envelope amplitudes.
- Calculate the modulation index.
- Demodulate the AM signal.
- Compare the recovered signal with the original message signal.

---

## Theory

Amplitude Modulation (AM) is a modulation technique in which the
amplitude of the carrier signal is varied according to the amplitude
of the message signal.

For proper envelope detection:

- Carrier frequency must be much greater than message frequency.
- The modulation index should not exceed unity for conventional
  AM without over-modulation.

### Types of Modulation

| Modulation Index | Type |
|---|---|
| M < 1 | Under modulation |
| M = 1 | Perfect modulation |
| M > 1 | Over modulation |

---

## Components

| Component | Specification |
|---|---|
| Breadboard | 830–840 tie points |
| DC Power Supply | ±12 V |
| Transistor | BC107 |
| Resistors | 470 kΩ, 22 kΩ, 10 kΩ, 1.2 kΩ, 1 kΩ |
| Capacitors | 0.1 µF, 0.01 µF |
| Diode | OA79 |
| CRO / DSO | 0–80 Vpp, 0–20 MHz |
| Function Generator | 0–15 Vpp |
| Potentiometer | 1 kΩ |

---

## Circuit

### AM Modulator

The AM modulator is implemented using the BC107 transistor
configuration specified in the laboratory manual.

### AM Demodulator

The demodulator uses a diode detector followed by an RC
low-pass filter for recovering the message signal.

---

## Proteus Simulation

Proteus files:

```text
Circuit/
├── AM_Modulator_Proteus.pdsprj
├── AM_Demodulator_Proteus.pdsprj
├── AM_Modulator.png
└── AM_Demodulator.png
```

## Experimental Setup

The circuit was implemented on a breadboard and tested using:

- Function generator
- DC power supply
- Oscilloscope

The AM waveform was observed on the oscilloscope.

## Modulation Index

The modulation index is calculated using:

M = (Vmax - Vmin) / (Vmax + Vmin)

It can also be calculated using:

M = Vm / Vc

where:

- Vmax = maximum envelope amplitude
- Vmin = minimum envelope amplitude
- Vm = amplitude of message signal
- Vc = amplitude of carrier signal

## Observation Table
| No. | Vmax (V) | Vmin (V) | M = (Vmax-Vmin)/(Vmax+Vmin) | Vm (V) | Vc (V) | M = Vm/Vc |
| --- | -------: | -------: | --------------------------: | -----: | -----: | --------: |
| 1   |  450mv   | 270mv    |      0.3mv                  | 9.45   | 6.25   | 1.512     |
| 2   |  500mv   | 300mv    |      0.4mv                  | 11.40  | 7.70   | 1.48      |
| 3   |  550mv   | 360mv    |      0.45mv                 | 12.25  | 8.95   | 1.40      |

## Demodulation

The AM signal is applied to the diode detector and RC low-pass filter.

The recovered output is compared with the original message signal. 

## Results

### AM Waveform
<img width="1917" height="1012" alt="image" src="https://github.com/user-attachments/assets/eee304cf-2272-4d01-9074-b865107849a9" />

Proteus Output
<img width="1375" height="872" alt="Screenshot 2026-10-10 225105" src="https://github.com/user-attachments/assets/540e180c-db19-44e2-b335-9998a8191664" />


### Demodulated Waveform
<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/80b93fd7-6869-4d7f-aab9-366d9e34f013" />

## Conclusion

The AM modulator and demodulator circuits were implemented and
tested. The AM waveform was observed on the oscilloscope and the
demodulated signal was compared with the original message signal.
