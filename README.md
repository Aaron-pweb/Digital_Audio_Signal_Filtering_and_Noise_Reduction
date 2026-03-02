# Digital Audio Signal Filtering & Noise Reduction

This project is a Python-based Digital Signal Processing (DSP) tool designed to filter and reduce noise in audio signals, specifically targeting `.wav` files. It applies advanced mathematical filters to remove unwanted frequencies and exports a clean, high-quality audio file.

---

## 🚀 Features
- **Noise Reduction:** Advanced filtering algorithms to clean audio data.
- **Waveform Visualization:** Before and after plots for visual analysis.
- **Support for .wav files:** Industry-standard audio format support.
- **Modern Tech Stack:** Built with leading Python DSP libraries.

---

## 🛠️ Tech Stack & Dependencies
This project utilizes the following industry-standard libraries:

*   **NumPy:** For core mathematical computations and handling audio data.
*   **SciPy (`scipy.signal`):** For signal processing and generating core filtering algorithms.
*   **Matplotlib:** For visualizing audio data and waveforms.
*   **Librosa:** For advanced audio analysis and feature extraction.
*   **SoundFile:** For reading and writing `.wav` files.

---

## 💻 Getting Started

### 1. Clone the Repository
Open your terminal or command prompt and run:

```bash
git clone git@github.com:Aaron-pweb/Digital_Audio_Signal_Filtering_and_Noise_Reduction.git
cd Digital_Audio_Signal_Filtering_and_Noise_Reduction
```

### 2. Set Up a Virtual Environment (Recommended)

#### 🐧 Linux / 🍎 macOS
```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### 🪟 Windows
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies
Once the virtual environment is activated, install the required packages:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Add to Jupyter (ipykernel)
To run the `.ipynb` notebook files in VS Code or Jupyter, you need to add your virtual environment as a kernel:

```bash
pip install ipykernel
python -m ipykernel install --user --name=dsp_env --display-name "Python (DSP Project)"
```

After running this, open `sound-filtter.ipynb` and select "Python (DSP Project)" from the kernel/interpreter menu.

---

## ☁️ Running on Google Colab
If you prefer not to install anything locally, you can run this project directly on Google Colab:

1.  Upload `sound-filtter.ipynb`, `requirements.txt`, and the `audio/` folder to your Google Drive.
2.  Open the notebook in Colab.
3.  Install dependencies in a Colab cell:
    ```python
    !pip install -r requirements.txt
    ```

---

## 🎧 How to Use
1.  Place your raw audio files in the `audio/` directory.
2.  Open `sound-filtter.ipynb` in your preferred editor (VS Code, Jupyter, or Colab).
3.  Follow the steps in the notebook to load, process, and save your clean audio.

---

## 📄 License
This project is open-source and available under the MIT License.
