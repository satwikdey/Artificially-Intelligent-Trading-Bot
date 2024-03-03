Artificially-Intelligent-Trading-Bot
Develop a bot capable of analyzing the sentiment of live news and events, and execute trades accordingly.
Follow-Up Steps to Run the Project:
Set up a virtual environment:
Create a virtual environment using conda: conda create -n trader python=3.10
Activate the environment: conda activate trader
Install initial dependencies:
Install required packages: pip install lumibot timedelta alpaca-trade-api==3.1.1
Install transformers and related libraries:
Install torch, torchvision, torchaudio, transformers: pip install torch torchvision torchaudio transformers
Update API_KEY and API_SECRET:
Obtain values from your Alpaca account and update the respective fields in the code.
Run the bot:
Execute the bot script: python tradingbot.py
Note:
Torch installation instructions may differ based on your OS and hardware. Refer to PyTorch Installation Instructions for more details.
If encountering an SSL error while accessing the Alpaca Trading API, install the necessary SSL certificates:
Download the intermediate SSL Certificates from the following URLs:
https://letsencrypt.org/certs/lets-encrypt-r3.pem
https://letsencrypt.org/certs/isrg-root-x1-cross-signed.pem
Change the file extensions of the downloaded files to .cer.
Double-click each file and follow the installation wizard, selecting all default options.
