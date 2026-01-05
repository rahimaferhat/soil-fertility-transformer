# Soil Fertility Assessment using Hyperspectral Imagery (Transformer)

This project implements a lightweight Transformer model to predict soil fertility (index) from hyperspectral imagery data. It is optimized for CPU training (e.g., Google Colab free tier).

## Features
- **Transformer Architecture**: Uses custom `PositionalEncoding` and Multi-Head Attention.
- **Robust Serialization**: Custom layers are registered for problem-free saving and loading.
- **Synthetic Data**: Includes a generator to create realistic synthetic hyperspectral data for testing.
- **Visualization**: Automatically plots training history and prediction performance.

## Files
- `soil_fertility_transformer_complete.py`: The main script that contains everything (Data Gen -> Model -> Train -> Save).

## How to Run

### In Google Colab
1. Open Google Colab.
2. Upload `soil_fertility_transformer_complete.py` or copy-paste its content.
3. Run the script.

### Locally
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the script:
   ```bash
   python soil_fertility_transformer_complete.py
   ```

## Model Output
The trained model and scalers are saved to `./models/` (or your Google Drive path if mounted).
