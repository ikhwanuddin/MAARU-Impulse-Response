# MAARU-Impulse-Response

## Laboratory-Generic Impulse Response in the Virtual Sound Environment

### Elevation:
- S01: -45 degree
- S02: -30 degree
- S03: -20 degree
- S04: -10 degree
- S05: 0 degree
- S06: 10 degree
- S07: 20 degree
- S08: 30 degree
- S09: 45 degree
- S10: 60 degree
- S11: 75 degree 
- S12: 90 degree

### Azimuth:
- 0 to 350 degree in 10 degree steps (36 azimuths) for S01-S11; S12 (zenith) azimuth 0 only
- 397 impulse responses in total. The 360 degree position repeats 0 degree and is not included.
- Files: `Lab_IR/Lab_IR_Sxx_aaa.wav` (xx = speaker, aaa = azimuth)

### Measurement setup:
- Date measured: 9 December 2024 (repeats of some positions on 11 December). Turret Laboratory, Imperial College London.
- Array: ReSpeaker 6-Mic (6 channels), ring radius 46.3 mm, lying flat and facing the zenith (the array normal points at S12), on a stand on an electric turntable.
- Sources: 12 fixed loudspeakers on an arc at about 1.5 m from the array (137-145 cm measured), array centre 155 cm above the floor; elevations as above.
- Turntable: turns clockwise seen from above, 10 degree steps from azimuth 0 (start position). The source is fixed, so the source direction seen from the array moves anticlockwise.
- Channels: with the ODAS configuration angles (0 degree at the left, increasing clockwise seen from the front when the array is upright), CH4 0 degree, CH5 60, CH0 120, CH1 180, CH2 240, CH3 300.
- Sweep: exponential, about 22 Hz to 22 kHz in 15 s, 48 kHz. The impulse responses are obtained by deconvolution with the inverse filter.

### Date:
Dataset assembled 21 August 2025 (the measurements are from December 2024).

### Visualizations:
![Lab IR Plots](Lab_IR/Lab%20IR%20Plots.png)

## Silwood Park Forest Impulse Response (SP_IR)

The dataset contains two sets of impulse responses (IR) collected in Silwood Park Forest.

### SP_IR1
Contains measurements with various azimuths and distances.
- **Location:** 51°24'43.0''N, 0°38'29.0''W
- **Azimuth:** 0, 60, 120, 180, 240, 300 degrees
- **Distance:** 2, 4, 8, 16 meters
- **Note:** `SP_IR_08m_060.wav` is a copy of `SP_IR_04m_060.wav`; the 8 m / 60 degree position was not recorded.
- **Date:** 15 June 2025

### Visualizations:
![SP IR Plots Part 1](SP_IR1/SP%20IR%20Plots%20Part%201.png)

### SP_IR2
Contains measurements at a fixed azimuth with varying distances, with 3 repetitions per measurement.
- **Location:** 51°24'43.0''N, 0°38'29.0''W
- **Azimuth:** 180 degrees
- **Distance:** 1, 2, 4, 8, 16, 32, 64 meters
- **Repetitions:** 1, 2, 3 (for each distance)
- **Date:** 23 July 2025

### Visualizations:
![SP IR Plots Part 2](SP_IR2/SP%20IR%20Plots%20Part%202.png)

## Cite this work
ikhwanuddin. (2026). ikhwanuddin/MAARU-Impulse-Response: MAARU IR v1.1 (v1.1). Zenodo. https://doi.org/10.5281/zenodo.20799384

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20799384.svg)](https://doi.org/10.5281/zenodo.20799384)
