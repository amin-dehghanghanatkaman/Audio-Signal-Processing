# Audio Signal Processing Approaches

In this repository we implemented the following methods/approaches for audio signal processing:

## Methods Implemented

- **Savitzky-Golay Filtering** - Denoising the audio signal while preserving important features like peaks and valleys using polynomial fitting.
- **Central/Temporal Velocity (First Derivative)** - Computing the rate of amplitude change over time using central difference method.
- **Acceleration (Second Derivative)** - Computing the rate of velocity change over time.
- **Rolling Mean and Standard Deviation** - Computing local statistical features over sliding windows.
- **Within-Patient Normalization** - Normalizing audio signals using Z-score and Min-Max methods to remove amplitude variations.
- **Skewness and Kurtosis** - Computing higher-order statistics of the amplitude distribution.
- **Composite Voice Instability Index** - Combining jitter (frequency variation) and shimmer (amplitude variation) into a single instability score.
- **Voice Quality Ratio (HNR/NHR)** - Computing Harmonics-to-Noise Ratio and Noise-to-Harmonics Ratio for voice quality assessment.


## Installation

```bash
git clone https://github.com/amin-dehghanghanatkaman/Audio-Signal-Processing.git
cd audio-signal-processing
pip install -r requirements.txt
