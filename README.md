# Aabar

**Tested on Ubuntu, python 3.12.4, please make sure that the libraries are well installed, make sure that scikit-learn version is 1.3.2, failing in that will cause the predictor to not work as expected, and make sure sure that the jwt library is pyjwt**

# Initialization:
```
python3 api_setup.py
```
# How to run (landing page):

```
npm i
npm run dev
```
# How to run (streamlit dashboard):

```
uvicorn fastapi_server:app --reload
streamlit run main.py
```
