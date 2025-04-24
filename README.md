# POEX

```
conda create -n poex python=3.11
conda activate poex

cd POEX
pip install -e .

cd Fastchat
pip install -e .

# set base_url and api key
cd src
python run_poex_qwen.py
```