# Mandible-SHAPE-Based-Sex-Estimation
mandible shape-based sex estimation tool



# Steps to Run App on local 
1. Delete the broken virtual environment

    Inside your project folder, run:
        
        rm -rf venv

2. Create a fresh virtual environment (recommended) Use python3:
    
    python3 -m venv venv

3. To Activate - ( Mac / Linux )

    source venv/bin/activate

3. To Activate on ( Windows )

    venv\Scripts\activate

4. Upgrade pip (recommended)

     pip install --upgrade pip

5. Install dependencies

    pip install -r requirements.txt

6. Google credentials setup (local run)


# Make sure:

google_credentials.json is in the same folder

Google Sheets & Drive APIs are enabled

Sheet access is shared with the service account email


6. Run the app

    streamlit run app.py

You’ll see output like:
    Local URL: http://localhost:8501


# deployed on streamlit cloud




