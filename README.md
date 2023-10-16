# Flight Fare Prediction - a Classic Time Series Project

* Flight fare prediction is a classical problem of time series forecasting that finds trends in past observations to outline the future
* Many popular flight booking websites today, including Google Flights, showcase important insights on:
  * Current fair status: high, low, or fair
  * Past fare trends, upcoming future trends, and
  * Helps decide the right time to book a flight ticket.
* In this project, we are going to build a Python Flight Fare Prediction App that returns the fare prediction for a given set of travel details, like:  departure date, arrival date, departure city, arrival city, stoppages, and the airline carrier.

## App Functionality

![](templates/App_Functionality.png)

## Steps to run Flight Fare App - on Windows

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://git-scm.com/downloads) Client
* Open GIT CMD >> navigate to working directory >> Clone this [GitHub Repo](https://github.com/ameer-ali-jamali/flight-price-prediction.git) (or download project files from GitHub directly)

  git clone https://github.com/ameer-ali-jamali/flight-price-prediction.git
* Open Windows Powershell >> navigate to a new working directory (cloned repo folder)
* Run Project in Flask (Using PIP + Virtualenv)

  pip install virtualenv                  # install virtual environment
  virtualenv ENV                          # create a virtual environment by the name ENV
  .\ENV\Scripts\activate                  # activate ENV
  pip install -r .\requirements.txt       # install project dependencies
  python app.py                           # run the project
  deactivate                              # close the virtual environment once done

### Steps to run Flight Fare App - on Mac

* Prerequisites: [Python 3.9
  ](https://www.python.org/downloads/)
* Open Terminal >> navigate to working directory >> Clone this [GitHub Repo](https://github.com/ameer-ali-jamali/flight-price-prediction.git) (or download project files from GitHub directly)

  git clone https://github.com/ameer-ali-jamali/flight-price-prediction.git
* Navigate to the project working directory (cloned repo folder)
* Run Project in Flask (Using PIP + Virtualenv)

  python -m venv venv              # Create a virtual environment
  source venv/bin/activate        # Activate the virtual environment (on Linux/macOS)
  pip install -r requirements.txt  # install project dependencies
  python app.py                         # run the project
  deactivate                              # close the virtual environment once

### Important Note for Python Version

If you encounter issues with Python version commands, such as `python --version` not working, please try using `python3 --version` instead.

Python 2 and Python 3 coexist on many systems, and the commands may vary depending on your Python installation. If you're unsure about which command to use, you can check the available Python versions with:

```bash
python --version
python3 --version
```



### Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/ameer-ali-jamali/flight-price-prediction/issues) by including your search query and the expected result.

### Important links:

* [Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)
* [Project Folder on Drive](https://drive.google.com/drive/folders/1vnapi048bbmoXyoxOLLX6W_tA6a1uQ9w?usp=sharing)
