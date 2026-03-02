# Digital Audio Signal Filtering & Noise Reduction

##  Description
This project is a Python-based Digital Signal Processing (DSP) script designed to filter and reduce noise in sound and audio signals. Specifically targeting `.wav` files, the tool reads raw audio data, applies mathematical filters to remove unwanted frequencies (noise), and exports a newly cleaned audio file. 


## Tech Stack & Dependencies
This project utilizes industry-standard Python DSP and data science libraries:

* **NumPy:** For core mathematical computations and handling audio data as large, fast arrays.
* **SciPy (`scipy.signal`):** For signal processing, optimization, and generating the core audio filter algorithms.
* **Matplotlib:** For visualizing the audio data (e.g., plotting the waveforms before and after filtering).
* **Librosa:** For advanced audio analysis and feature extraction.
* **SoundFile:** For cleanly reading the original `.wav` files and writing the final filtered audio back to disk.

## Getting Started

### Prerequisites
Make sure you have Python installed on your system. It is recommended to run this in a virtual environment.

### Installation
Install the required packages using pip:

```bash
pip install -r requirements.txt
