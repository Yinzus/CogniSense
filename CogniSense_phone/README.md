# alzphone-screener
See README in previous cell if truncated. Quick start:
1) `python -m venv .venv && source .venv/bin/activate`
2) `pip install -r requirements.txt`
3) `python alz_capture.py --seconds 5 --no-preview`
4) Edit `dataset.csv`
5) `python alz_train.py --csv dataset.csv --out model.pkl`
6) `python alz_capture_v2.py --model model.pkl`
