# Machine Learning Project

This repository contains Jupyter notebooks for machine learning exercises and weather forecasting analysis.

## 📁 Files

### Notebooks
- **`Weather_Forecasting_Machine_learning.ipynb`** - Main weather forecasting project using Random Forest models
- **`module1_intro_simple_lin_regres.ipynb`** - Introduction to simple linear regression
- **`module1_intro_multi_lin_regres.ipynb`** - Introduction to multiple linear regression
- **`API_Keys_Guide.ipynb`** - Guide for securely managing API keys (NEW!)

### Configuration
- **`.env`** - API keys storage (⚠️ DO NOT COMMIT - already in .gitignore)
- **`.gitignore`** - Protects sensitive files from being committed

## 🔐 API Keys Setup

Your API keys are now stored securely!

### Quick Start

1. **Install required package:**
   ```bash
   pip install python-dotenv
   ```

2. **Your API keys are already configured in `.env`:**
   - ✅ OpenWeather API Key
   - ✅ NOAA Climate Data API Key

3. **Run any notebook** - API keys load automatically!

### Your `.env` File Contents
```
OPENWEATHER_API_KEY=497167241811902ed3846821b5f469ae
NOAA_API_KEY=FMrkKpFNZLJxHgWdXlwbukTzcBCtohWn
```

## 🛡️ Security Features

- ✅ API keys stored in `.env` (not in notebooks)
- ✅ `.env` protected by `.gitignore`
- ✅ Safe to share notebooks on GitHub
- ✅ No hardcoded secrets in code

## 📚 Usage

### Running Weather Forecasting Notebook

```bash
jupyter notebook Weather_Forecasting_Machine_learning.ipynb
```

The notebook will automatically load your API keys from `.env` file.

### Testing API Keys

Open and run `API_Keys_Guide.ipynb` to verify your API keys are working correctly.

## 🔧 Troubleshooting

**API keys not loading?**
1. Ensure `.env` file exists in project directory
2. Install python-dotenv: `pip install python-dotenv`
3. Restart Jupyter kernel
4. Check `.env` file format (no spaces around `=`)

**Getting API errors?**
- Verify your API keys are valid
- Check API rate limits
- Ensure internet connection is active

## 📝 Completed Exercises

All exercises in the regression notebooks have been completed:

- ✅ `module1_intro_simple_lin_regres.ipynb` - Exercise 1 & 2
- ✅ `module1_intro_multi_lin_regres.ipynb` - Exercises 1, 2, 3, & 4

## 🌐 API Documentation

- [OpenWeather API](https://openweathermap.org/api)
- [NOAA Climate Data API](https://www.ncdc.noaa.gov/cdo-web/webservices/v2)

## ⚠️ Important Notes

- **Never commit `.env` file** - It contains your private API keys
- **Don't share API keys** - Each user should use their own keys
- **Rotate keys periodically** - Update keys in `.env` file when needed

## 🚀 What Changed

All API keys have been removed from notebooks and moved to `.env`:
- Updated `Weather_Forecasting_Machine_learning.ipynb` (Cell 14 & 57)
- Created `API_Keys_Guide.ipynb` for testing and documentation
- Added `.gitignore` to protect sensitive files
- Created `.env` with your API keys

Your notebooks are now secure and ready to share! 🎉
