# CoCoNote: AI Data Wrangling Code Generator

## What It Does
Converts English to Python/pandas code. Example: "Clean missing values" → `df.fillna()`

## 5-Minute Quick Start

1. Open Google Colab → Enable GPU (Runtime → T4 GPU)
2. Run Cell 1 → Mounts Google Drive
3. Run Cell 2 → Clones repository
4. Run Cell 3 → Installs packages
5. Run Cell 4 → Downloads dataset (1.9GB)
6. Run Cell 8k → Trains model (30 seconds)
7. Run Cell 23 → Launches web GUI

## All 40 Cells - What They Do

| Cells | What Happens | Time |
|-------|--------------|------|
| 1-4 | Setup, download data | 5 min |
| 5-7 | Create code files | 10 sec |
| 8-8f | Fix dataset issues | 30 sec |
| 8k | Train model | 30 sec |
| 9-13 | Show charts, save model | 10 sec |
| 14-19 | Test with 10 prompts | 10 sec |
| 20-24 | Build web interface | 10 sec |
| 32-40 | Show before/after | 10 sec |

## Training Results

| Epoch | Loss |
|-------|------|
| 1 | 1.01 |
| 2 | 0.95 |
| 3 | 0.90 |
| 4 | 0.84 |
| 5 | 0.77 |

**Improvement: 24%**

## Files You Get

- `simple_model.pt` - Trained model
- `model_package.zip` - Download this
- `training_progress.png` - Loss chart
- `model_predictions.csv` - Results
- `before_after_results.xlsx` - Excel file

## Common Problems & Fixes

| Problem | Fix |
|---------|-----|
| Out of memory | Reduce batch_size |
| No GPU | Runtime → Change runtime → T4 |
| JSON error | Run Cell 8f |
| Model missing | Run Cell 8k |

## Quick Commands

```
!python ultra_simple_train.py                    # Train
files.download('model_package.zip')              # Download
demo.launch(share=True)                          # Start GUI
```
