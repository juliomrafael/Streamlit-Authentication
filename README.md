# Streamlit-Authentication
 Python Streamlit authentication based on [Arvindra repo](https://github.com/asehmi/auth-simple-for-streamlit)

### Quick start
1. On your root directory
2. Copy the sample environment settings file env.sample to .env
3. Install requirements
pip install -r requirements.txt
4. Initialize the SQLite database and create some users (including at least one super user)
streamlit run admin.py
5. Finally, run the test application
streamlit run app.py