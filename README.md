<h1 align="center">Short-term forecast of <br> onshore windturbines oscillation kinematics</h1>

<img src="https://www.ge.com/renewableenergy/sites/default/files/2020-01/onshore-hero5.jpg"/>

<h2 align="center">Intuitive and helpful models for <br> statistical analysis and shortterm forecasting <br> of measurement data.</h2>

<div align='center'>
  
<a href='https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast/releases'>
  
<img src='https://img.shields.io/github/release/WindIO-Bachelorthesis/Shortterm_Forecast?color=%23FDD835&label=version&style=for-the-badge'>
  
</a>
  
<a href='https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast/blob/main/LICENSE'>
  
<img src='https://img.shields.io/github/issues/WindIO-Bachelorthesis/Shortterm_Forecast?style=for-the-badge'>
  
<a href='https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast/blob/main/LICENSE'>
  
<img src='https://img.shields.io/github/license/WindIO-Bachelorthesis/Shortterm_Forecast?style=for-the-badge'>
  
</a>
  
<br>
<br>
  
![Python](https://img.shields.io/badge/PYTHON-v3.6-blue.svg)
  
</div>


<br>

### 📖 CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Tech stack
 * Folder Structure
 * Dataset
 * Forecasting Models
 * CONTACT Elements for IoT Integration
 * Installation
 * Usage
 * References
 * License

<br>

## 📝 Introduction
Onshore wind already provides a substantial part of the energy mix ⚡ today. In order to further reduce the costs 💲, the installation process in particular should be improved.
The installation of the blades is the greatest challenge. Relative movements between the nacelle and the blade root make the installation difficult. If the relative movement exceeds a certain threshold value, installation is no longer possible and there is an expensive delay.
Based on measurement data 📊 that were recorded during the installation of wind turbines, machine learning 🤖 models and neuronal networks are intended to predict the oscillation kinematics for a defined period of time.

This repository contains three different [forecasting models](https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast/tree/main/models), which are available as jupyter notebooks, a CONTACT Elements for IoT [integration](https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast) and an associated [thesis](https://github.com/WindIO-Bachelorthesis/Shortterm_Forecast/thesis).

<br>

## 👨‍💻 Tech Stack

Front-End

<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
<a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a>
<a href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40"/> </a>
<a href="https://jestjs.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> </a>
<a href="https://plotly.com/javascript/" target="_blank" rel="noreferrer"> <img src="https://plotly.com/all_static/images/dark-logo.png" alt="plotlyjs" width="40" height="40"/> </a>

Back-End

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<a href="https://www.contact-software.com/de/" target="_blank" rel="noreferrer"> <img src="https://www.contact-software.com/design/img/logo-icon.svg" alt="PowerScript" width="40" height="40"/> </a>

Database

<a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a>
<a href="https://www.influxdata.com/" target="_blank" rel="noreferrer"> <img src="https://assets.zabbix.com/img/brands/influxdb.svg" alt="influxDB" width="40" height="40"/> </a>

Machine Learning & Neuronal Networks

<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
<a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a>
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a>
<a href="https://www.statsmodels.org/dev/about.html" target="_blank" rel="noreferrer"> <img src="https://www.statsmodels.org/dev/_static/statsmodels-logo-v2-bw.svg" alt="statsmodels" width="40" height="40"/> </a>
<a href="https://facebook.github.io/prophet/" target="_blank" rel="noreferrer"> <img src="https://facebook.github.io/prophet/static/logo.svg" alt="prophet" width="40" height="40"/> </a>

<br>

## ⚠️ License
This repository uses the [MIT](https://choosealicense.com/licenses/mit/) license. Please see the LICENSE.md file for more details.
