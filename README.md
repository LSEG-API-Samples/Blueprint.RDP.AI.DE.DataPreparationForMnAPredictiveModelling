# Data Engineering - Data preparation for M&A predictive modelling


## <a id="overview"></a>Overview
After closely examining the data during the data exploration phase, we need to prepare them for subsequent mining. The data preparation phase includes data cleaning, selection, outlier removal and more. Additionally, datasets or elements may be merged or aggregated in this step.

This guide will walk through the data preparation process of the M&A dataset we have aquired in the Data Ingestion phase. To learn more about the business incentive and data aquisition process of to be analysed datasets please visit here. For additional information on the actual model trained on the dataset can be found here.

First thing we need to do is to load the datasets add the labels and merge them.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [plotly](https://pypi.org/project/plotly/), [scipy](https://pypi.org/project/scipy/), [statsmodels] (https://pypi.org/project/statsmodels/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan**
