# Evaluation of deep learning architectures for short-term price forecasting in the Spanish electricity market

This project was conducted as part of the requirements of the "Deep Neural Networks" postgraduate course (Fall 2019) at the UoA (MSc in Data Science and Information Technologies).

In this project, we compare different deep neural network architectures (+XGBoost) on the task of predicting the next hour's electricity price by using the past values of the electricity price as well as those of another features related to energy generation and weather conditions of 5 major cities in Spain. Furthermore, the project contains a meticulous exploration and cleaning of the data, time series analysis of the electricity price and careful feature engineering. With further research and development (e.g. as a forecasting model which is updated in real-time) this kernel could possibly prove useful to all of the stakeholders (electric power companies, investors, etc.) involved in energy markets.

---
## Contents

- **Presentation:** `roussis_presentation_dnn.pdf`
This is the presentation that was presented to the instructors of the course, as well as to the other students of the course. The interested reader is referred to the report of the project which is more detailed.
- **Report:** `roussis_report_dnn.pdf` 
The report of the project includes a detailed analysis of the case study, the methodology that was followed, the final results of the experiments and the references that were used.
- **Jupyter Notebook:** `roussis_project_dnn.ipynb` 
The full code of the project is contained in this single Jupyter notebook, as specified by the instructors.
- **Neural Net Images:**
The images of the neural network architectures that were used in the project. They were created using [Netron](https://github.com/lutzroeder/netron) and are included in the report as well as the presentation of the project.
---
## Usage

In order to reproduce the contents of the Jupyter notebook, follow these steps:
1. Download the original dataset which was uploaded to Kaggle by Nicholas Jhana from  [here](https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather).
2. Clone this repository or download the two files which are absolutely necessary (`roussis_project_dnn.ipynb` and `environment.yml`)
3. Create a conda environment with all the required libraries:
`$ conda env create -f environment.yml`
4. Run the code in the Jupyter notebook. Please be aware that _not all the results contained in the presentation and the report are directly generated by the notebook_; however, feel free to change the parameters in order to reproduce them.
---
## Additional information

You can find a different and shorter version of the project in  [this Kaggle kernel](https://www.kaggle.com/dimitriosroussis/electricity-price-forecasting-with-dnns-eda).
