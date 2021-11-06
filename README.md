<h1 align="center">Short-term forecast of <br> onshore windturbines oscillation kinematics</h1>

<img src="https://www.ge.com/renewableenergy/sites/default/files/2020-01/onshore-hero5.jpg"/>

<h2 align="center">Intuitive and helpful models for <br> statistical analysis and shortterm forecasting <br> of measurement data.</h2>

### CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Installation
 * Usage
 * Contributing
 * License


## Introduction
Offshore and onshore wind already provides a substantial part of the energy mix ⚡ today. In order to further reduce the installation costs 💲, the installation process in particular should be improved.
The installation of the blades is the greatest challenge. Relative movements between the nacelle and the blade root make the installation difficult. If the relative movement exceeds a certain threshold value, installation is no longer possible and there is an expensive delay.
Based on measurement data 📊 that were recorded during the installation of wind turbines, machine learning 🤖 models are intended to predict the oscillation kinematics for a defined period of time.

There are five different model types to chose from:
- Auto-Regressive Integrated Moving Average (ARIMA)
- Seasonal Autoregressive Integrated Moving Average (SARIMA)
- Generalized AutoRegressive Conditional Heteroscedasticity (GARCH) 
- Long short-term memory (LSTM)




## Installation
Execute the following commands in a shell to start the web app frontend on your local development environment.

```
$ git clone https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast
$ cd Shortterm_Forecast
$ pip install requirements.txt
$ jupyter notebook
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
