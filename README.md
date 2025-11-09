# Pack SGA %Pack Prediction - ML Deployment

## Overview
Machine learning model to predict packing efficiency (%Pack) in SGA production.

## Model Performance
- **Best Model:** Random Forest
- **Test R² Score:** 0.7888
- **RMSE:** 0.0442
- **MAE:** 0.0160

## Files Included
1. `pack_model.pkl` - Trained model with preprocessing pipeline
2. `app.py` - Streamlit web application
3. `requirements.txt` - Python dependencies
4. `model_summary.xlsx` - Model comparison & feature importance
5. `01-09_*.png` - 9 visualization charts (Minitab style)

## Quick Start

### Local Deployment
```bash
pip install -r requirements.txt
streamlit run app.py
```

### Cloud Deployment (Recommended)

**Option 1: Streamlit Cloud (Free)**
1. Push to GitHub
2. Visit share.streamlit.io
3. Connect repository
4. Deploy!

**Option 2: Hugging Face Spaces**
1. Create account on huggingface.co
2. New Space → Streamlit
3. Upload files
4. Auto-deploy

**Option 3: Railway**
1. Sign up at railway.app
2. New Project → Deploy from GitHub
3. Set start command: `streamlit run app.py --server.port $PORT`

## Features
- 🔮 Single prediction with interactive inputs
- 📊 Batch prediction from CSV/Excel
- 📈 Model analytics & visualizations
- 📥 Download prediction results

## Usage
1. Navigate to "Single Prediction" for individual estimates
2. Use "Batch Prediction" for multiple records
3. Check "Model Analytics" for performance insights

## Support
Contact your data science team for assistance.

**Created by:** Kyoko (MIT USA)
**Date:** 2025-11-09
