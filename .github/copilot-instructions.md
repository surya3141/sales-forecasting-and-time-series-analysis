<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# Sales Forecasting & Time Series Analysis - Copilot Instructions

## Project Context
This is a comprehensive time series analysis and sales forecasting project demonstrating advanced statistical and machine learning techniques for business forecasting applications.

## Key Guidelines for Code Generation

### Time Series Best Practices
- Always check for stationarity before applying ARIMA models
- Use proper time series cross-validation (walk-forward validation)
- Include seasonality analysis and decomposition
- Handle missing values appropriately for time series data
- Set proper datetime index and frequency for time series operations

### Forecasting Workflow
- Start with exploratory data analysis (trend, seasonality, outliers)
- Test multiple models: Classical (ARIMA/SARIMA), Modern (Prophet), ML (XGBoost)
- Use appropriate evaluation metrics: MAPE, RMSE, MAE for business context
- Generate confidence intervals and uncertainty quantification
- Validate models using time series specific techniques

### Code Structure
- Use modular functions for different forecasting approaches
- Include proper error handling for time series operations
- Add comprehensive docstrings for statistical functions
- Follow time series naming conventions (ts, forecast, residuals)
- Create reusable utility functions for common operations

### Statistical Analysis
- Perform stationarity tests (ADF, KPSS) before modeling
- Use ACF/PACF plots for ARIMA parameter selection
- Include residual analysis and diagnostic plots
- Test for seasonality using statistical tests
- Document assumptions and model limitations

### Visualization Guidelines
- Create interactive Plotly charts for forecasting dashboards
- Use consistent time axis formatting across all plots
- Include forecast uncertainty bands and confidence intervals
- Generate seasonal decomposition plots
- Add business-friendly annotations and labels

### Business Focus
- Frame analysis in terms of revenue impact and ROI
- Provide actionable insights for inventory and marketing
- Include scenario analysis (optimistic/pessimistic forecasts)
- Quantify business risks and opportunities
- Create executive-ready summary visualizations

### Prophet Specific
- Use appropriate seasonality settings (yearly, weekly, daily)
- Add holiday effects and special events
- Tune seasonality parameters based on data characteristics
- Include trend changepoint detection and analysis
- Document Prophet model assumptions and limitations

### ARIMA/SARIMA Guidelines
- Use information criteria (AIC, BIC) for model selection
- Perform proper differencing to achieve stationarity
- Include seasonal differencing for seasonal patterns
- Validate model assumptions through residual analysis
- Document parameter selection methodology
