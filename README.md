# RASA bot template (bootstrap)
    
## Minimal / Recommended Requirements
Dual Core CPU / Quad Core CPU
8 GB RAM / 16 GB RAM
20 GB / 50 GB Free Disk Space
    
## Quick Start (Ubuntu, t2.micro, 30GB)
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.8
sudo apt install python3.8-venv

git clone <THIS REPOSITORY>
cd <THIS REPOSITORY>

python3.8 -m venv env
source env/bin/activate
pip install --upgrade pip
pip install rasa --no-cache-dir

rasa train

rasa run actions --actions actions &

rasa shell
```

Rasa CLI:  https://rasa.com/docs/rasa/command-line-interface
