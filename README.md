# NUKE Hackathon

### Quick Start ###

```bash
git clone https://github.com/ErlendHaa/nukehack.git
cd nukehack
virtualenv venv
source venv/bin/activate
python -m pip install -r requirements.txt
nbstripout --install # install git filters
cd notebooks
jupyter notebook
```

Notebooks are not git friendly. To improve their friendlyness we use the git
filter [nbstripout](https://github.com/kynan/nbstripout).
```
