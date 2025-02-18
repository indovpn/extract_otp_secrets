```
brew install pipx
pipx install virtualenv
pipx ensurepath

virtualenv production
source production/bin/activate

pip install -U -r requirements.txt
python src/extract_otp_secrets.py example_export.txt
python src/extract_otp_secrets.py qr.jpg
```
