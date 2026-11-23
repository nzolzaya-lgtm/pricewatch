# PriceWatch: simple Streamlit Cloud upload

1. Unzip PriceWatch_Cloud_Fix.zip on your Mac.
2. Open the GitHub repository connected to your existing PriceWatch Streamlit app.
3. Upload these two files at the repository root: app.py and requirements.txt.
4. Replace the existing files and commit the changes. Do not upload the ZIP itself.

Keep Streamlit's entry point as app.py. Streamlit Community Cloud will rebuild
after the GitHub commit. Existing additional project files can stay in place;
this app.py uses its bundled code, stylesheet and real data.

This edition contains the same NSO snapshot: 179,405 reported prices across
22 places, December 2010 through October 2026. No invented prices are added.
The source snapshot and checksums are embedded and verified before loading.

For local use: pip install -r requirements.txt, then streamlit run app.py.
The provided source was tested with Python 3.12 and Streamlit 1.45.1.

The modular project remains the best version for editing and refreshing data.
