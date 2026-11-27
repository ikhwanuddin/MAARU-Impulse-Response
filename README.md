# MAARU-Impulse-Response

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17391527.svg)](https://doi.org/10.5281/zenodo.17391527) [![JASA](https://img.shields.io/badge/JASA-10.1121%2F10.0046897-007ec6)](https://doi.org/10.1121/10.0046897) [![Citations](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.crossref.org%2Fworks%2F10.1121%2F10.0046897&query=%24.message.is-referenced-by-count&label=citations&color=007ec6)](https://doi.org/10.1121/10.0046897) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

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
- Channels: board labels MIC1-MIC6 are CH0-CH5, numbered clockwise seen from the mic side. Seen from the mic side with CH0 and CH1 as the top pair: CH0 upper left, CH1 upper right, CH2 right, CH3 lower right, CH4 lower left, CH5 left (angles from the right edge, increasing anticlockwise: CH2 0 degree, CH1 60, CH0 120, CH5 180, CH4 240, CH3 300). At turntable azimuth 0 the top edge of the board (between CH0 and CH1) faces the loudspeaker arc.
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
ikhwanuddin. (2026). ikhwanuddin/MAARU-Impulse-Response: MAARU IR v1.2 (v1.2). Zenodo. https://doi.org/10.5281/zenodo.17391527

The DOI above always resolves to the latest version. Each version also has its own DOI, listed on the Zenodo record.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17391527.svg)](https://doi.org/10.5281/zenodo.17391527)

## Related publication
These impulse responses are the beamforming steering vectors used in:

Ikhwanuddin, R., Le Penru, N. P., Sethi, S. S., and Picinali, L. (2026). "A comparative evaluation of lab-generic and site-specific impulse response-based beamforming for enhanced automated bird call detection," J. Acoust. Soc. Am. 160(5), 3754–3769. https://doi.org/10.1121/10.0046897

[![JASA](https://img.shields.io/badge/JASA-10.1121%2F10.0046897-007ec6)](https://doi.org/10.1121/10.0046897) [![Citations](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.crossref.org%2Fworks%2F10.1121%2F10.0046897&query=%24.message.is-referenced-by-count&label=citations&color=007ec6)](https://doi.org/10.1121/10.0046897)

## License
The data in this repository are released under the [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE). You may share and adapt them for any purpose, as long as you credit the source by citing the dataset above.
