# Mandible-SHAPE-Based-Sex-Estimation
mandible shape-based sex estimation tool



# Steps to Run App on local 
1. Create virtual environment (recommended)
    
    python -m venv venv

2. To Activate - ( Mac / Linux )

    source venv/bin/activate

2. To Activate on ( Windows )

    venv\Scripts\activate

4. Install dependencies

    pip install -r requirements.txt

5. Google credentials setup (local run)

Uncomment this in your code:
    SERVICE_ACCOUNT_FILE = "google_credentials.json"
And replace:
        creds = Credentials.from_service_account_file(
        SERVICE_ACCOUNT_FILE, scopes=SCOPES
    )

# Make sure:

google_credentials.json is in the same folder

Google Sheets & Drive APIs are enabled

Sheet access is shared with the service account email


6. Run the app

    streamlit run app.py

You’ll see output like:
    Local URL: http://localhost:8501


# deployed on streamlit cloud




