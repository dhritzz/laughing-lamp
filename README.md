---
title: Vits Models
emoji: 🏃
colorFrom: pink
colorTo: indigo
sdk: gradio
sdk_version: 3.17.0
app_file: app.py
pinned: false
license: apache-2.0
---

Run:
nvidia-smi
sudo apt-get install python3.8 python3.8-dev python3.8-distutils libpython3.8-dev
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.8 114514
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py --force-reinstall

apt install git-lfs
git lfs install
git clone https://github.com/dhritzz/laughing-lamp
%cd vits-models

python3 -m pip install pip==21.3.1
python3 -m pip install -r requirements.txt
python3 app.py --share --device cuda --all
