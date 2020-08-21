# Bank of America QWIM Project: Applications of machine learning for empirical asset pricing and risk premia forecasting
# TeamName:Saraye

This project is about implementing machine learning techniques on empirical asset pricing and risk premia forecasting. 

Machine learning has gained enormous popularity for asset price forecasting in recent research studies. This project presents a comprehensive analysis of some of the "most promising" machine learning methods demonstrated in literature. In this study, 8 selected forecasting methods will be applied to time series, and the predicted time series will be analyzed based on 7 portfolio optimizers. By conducting the performance measurement, we identify the best performing models and trace their advantages and disadvantages.

### Instructions for forecast model fitting:
There are 8 forecasting methods - Naive forecaster, Exponential Smoothing, Theta forecaster, KNN regression, Random Forest, Pipeline Model, Vector Autoregression, and ESRNN. In the *Forecast Model Fit* folder, run *Capstone Project - Model Fitting.ipynb* in Python Jupyter notebook or Google Colab. The input data *DATA.xlsx* needs to be in the same location where *Capstone Project - Model Fitting.ipynb* is run. **！Warning:** ESRNN is placed seperately from all other models, as it takes hours to run this model and it is advised that you use a computer with GPU to build this model.

\
This QWIM project also includes Portfolio Optimization Analysis. Incorporating portfolio optimization analysis, we can gain extensive perspectives by comparing different forecasting methods and looking at **Portfolio Metrics** within each forecasting methods. In this section, several portfolio optimization methods commonly used in the industry and in academia are introduced, including Mean Variance, Minimum Variance, Maximum diversification, hierarchical risk parity, Black-Litterman, and CLA(robust version). 

### Instructions for portfolio optimization:
In the *Portfolio Optimization* folder, run each optimizer file marked by their name. The input for optimizer is the prediction result from forecast model fitting. Be sure to have the prediction result in the same location where the optimizers are located. in our case, the predicted results are named as *predictionreturn.xlsx*.

### Getting in touch
If you would like to reach out for any reason, be it debugging or just for a chat, please do so via our email: \
Raye Shen <rs6981@nyu.edu>\
Sarah Guo <yg2060@nyu.edu>\
Yu-Ting Chen <ytc343@nyu.edu>
