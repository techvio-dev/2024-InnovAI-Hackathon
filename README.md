# Aabar

Aabar is a centralized web app designed to monitor and manage underground water resources. It simplifies the well drilling licensing process, ensures compliance with water regulations, and predicts water availability using advanced data analytics. The app aims to combat illegal drilling and promote sustainable water management. Its target market includes government agencies, agricultural businesses, environmental organizations, and research institutions focused on water conservation. 

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
