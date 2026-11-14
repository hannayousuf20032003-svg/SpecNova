# SpecNova

### AI-Powered Molecular Identification Using MS/MS Spectra

SpecNova is an AI-powered molecular identification system designed to analyze tandem mass spectrometry (MS/MS) spectra and identify potential molecular structures.

By combining deep learning with molecular fingerprint matching, SpecNova predicts molecular fingerprints from input spectra and uses them to retrieve and rank candidate compounds from a molecular database.

## How It Works

SpecNova follows a multi-stage identification pipeline:

1. **Spectrum Input:** Receives MS/MS spectral data consisting of m/z and intensity values.
2. **Spectrum Preprocessing:** Processes and prepares the input spectrum for model inference.
3. **Molecular Fingerprint Prediction:** Uses a pretrained FPNet model to predict molecular fingerprints.
4. **Candidate Retrieval:** Filters molecular candidates based on precursor mass.
5. **Fingerprint Matching:** Compares predicted fingerprints against candidate molecular fingerprints.
6. **Candidate Ranking:** Ranks potential molecular structures based on their matching scores.

## Key Features

- AI-based molecular fingerprint prediction.
- MS/MS spectrum preprocessing.
- Precursor mass-based candidate filtering.
- Molecular fingerprint similarity scoring.
- Ranked molecular candidate identification.
- Chemical information retrieval, including molecular formulas and SMILES.

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Google Colab
- FPNet

## Getting Started

The project notebook can be opened directly in Google Colab.

1. Open `SpecNova.ipynb`.
2. Upload or connect the required model and dataset files.
3. Run the notebook cells in order.
4. Provide MS/MS spectral data to obtain ranked molecular candidates.

## Project Goal

SpecNova aims to support molecular identification by integrating deep learning-based molecular fingerprint prediction with candidate retrieval and ranking from MS/MS spectral data.
