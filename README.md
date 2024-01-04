# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *binance*
```
conda create -n binance python=3.7.9
```
Secondly, we will login to the *binance* environment
```
conda activate binance
```

###  Download GitHub repo

```
git clone https://github.com/Raikirimaru/binance_web_app.git
```

###  Pip install libraries
```
pip install -r requirements.txt
```

###  Launch the app

```
streamlit run app.py
```
