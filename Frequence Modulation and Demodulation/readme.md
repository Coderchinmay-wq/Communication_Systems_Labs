# Experiment 03 – Frequency Modulation and Demodulation

## Communication Systems Laboratory

---

## Aim

To generate a Frequency Modulated (FM) signal using IC 8038 and
study the modulation and demodulation process.

---

## Objectives

- Understand the principle of Frequency Modulation.
- Generate an FM signal using IC 8038.
- Observe the carrier and modulated waveforms.
- Measure the maximum and minimum frequencies of the FM signal.
- Calculate the frequency deviation.
- Calculate the FM modulation index.
- Calculate frequency sensitivity.
- Determine the bandwidth of the FM signal.
- Demodulate the FM signal.
- Observe and verify the recovered signal.

---

## Theory

Frequency Modulation (FM) is a modulation technique in which the
frequency of the carrier signal is varied according to the
instantaneous amplitude of the message signal.

In FM:

- The amplitude of the carrier remains constant.
- The frequency of the carrier varies according to the message
  signal.
- The amount of change in carrier frequency is called frequency
  deviation.
- Maximum frequency deviation occurs at maximum amplitude of the
  modulating signal.
- Minimum frequency deviation occurs at minimum amplitude of the
  modulating signal.

### Basic FM Concept

For a message signal:

\[
m(t) = A_m \cos(2\pi f_m t)
\]

the instantaneous frequency of the carrier varies according to
the amplitude of the message signal.

---

## Components and Equipment

| Sl. No. | Component / Equipment | Specification |
|---|---|---|
| 1 | Breadboard | 830–840 tie points |
| 2 | DC Power Supply | ±12 V |
| 3 | Waveform Generator | IC 8038 |
| 4 | Resistors | 100 kΩ, 82 kΩ, 10 kΩ, 1 kΩ |
| 5 | Capacitors | 0.1 µF, 100 pF, 1 µF |
| 6 | Diode | OA79 |
| 7 | CRO / DSO | 0–80 Vpp, 20 MHz |
| 8 | Function Generator | 0–15 Vpp |
| 9 | Centre-Tapped Transformer | 10.7 MHz |

---

## Circuit Design

### FM Modulator

The FM modulator was implemented using **IC 8038**.

The modulating signal is applied to the circuit and the frequency
of the carrier is varied according to the amplitude of the
modulating signal.

### FM Demodulator

The FM signal is applied to the demodulator circuit to recover the
original message signal.

---

## Circuit Diagram

### FM Modulator

![FM Modulator Circuit](Circuit/FM_Modulator.png)

### FM Demodulator

![FM Demodulator Circuit](Circuit/FM_Demodulator.png)

---

## Experimental Procedure

1. Rig up the circuit as shown in the circuit diagram.
2. Switch ON the power supply.
3. Observe the unmodulated sinusoidal carrier signal and measure
   its amplitude and frequency.
4. Apply the modulating signal with an amplitude of approximately
   1 V peak and frequency of 500 Hz.
5. Observe the frequency-modulated output.
6. Measure the minimum and maximum frequencies of the FM signal.
7. Calculate the frequency deviation and other FM parameters.
8. Apply the FM signal to the demodulator circuit.
9. Observe the demodulated output.
10. Compare the recovered signal with the original modulating
    signal.

---

## Experimental Parameters

### Modulating Signal

| Parameter | Value |
|---|---:|
| Amplitude, Am | ___ V |
| Frequency, Fm | ___ Hz |

### Carrier Signal

| Parameter | Value |
|---|---:|
| Carrier frequency, Fc | ___ Hz |
| Carrier amplitude, Ac | ___ V |

---

## FM Measurements

The following quantities were measured from the experimental
waveform:

- Maximum frequency, Fmax
- Minimum frequency, Fmin
- Frequency deviation, ΔF
- Modulation index, β
- Frequency sensitivity, Kf
- Bandwidth

---

## Calculations

### 1. Frequency Deviation

According to the laboratory manual:

\[
\Delta F = F_{max} - F_{min}
\]

Therefore,

```text
Fmax = ______ Hz

Fmin = ______ Hz
```
ΔF = Fmax - Fmin

ΔF = ______ Hz

### 2. FM Modulation Index

$$ \beta = \frac{\Delta F}{F_m} $$

where:

- β = FM modulation index
- ΔF = frequency deviation
- Fm = modulating frequency​

ΔF = ______ Hz

Fm = ______ Hz

β = ______

### 3. Frequency Sensitivity

$$ K_f = \frac{\Delta F}{A_m} $$

where:

- Kf = frequency sensitivity
- ΔF = frequency deviation
- Am = amplitude of modulating signal

ΔF = ______ Hz

Am = ______ V

Kf = ______ Hz/V

### 4. FM Bandwidth

The bandwidth is calculated using:

$$ BW = 2(\Delta F + F_m) $$

ΔF = ______ Hz

Fm = ______ Hz

BW = ______ Hz

## Observation Table
| Fmax (Hz) | Fmin (Hz) | ΔF (Hz) |  β | Kf (Hz/V) | BW (Hz) |
| --------: | --------: | ------: | -: | --------: | ------: |
|           |           |         |    |           |         |

## Expected Waveforms
### Message Signal

The message signal is a low-frequency sinusoidal signal.

### Carrier Signal

The carrier is a high-frequency sinusoidal signal with constant
amplitude.

### Frequency Modulated Signal

The amplitude remains approximately constant while the spacing
between successive cycles varies according to the message signal.

## Experimental Results
### FM Waveform

### Demodulated Waveform

## Practical Implementation

The FM modulator and demodulator circuits were implemented on a
breadboard and tested using laboratory equipment.

Breadboard Implementation

Laboratory Setup

Proteus Simulation

The circuit can also be simulated using Proteus.
