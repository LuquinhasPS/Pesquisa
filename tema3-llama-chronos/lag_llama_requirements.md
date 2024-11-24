Para execução do Lag-Llama seguindo as intruções de https://medium.com/@odhitom09/lag-llama-an-open-source-base-model-for-predicting-time-series-data-2e897fddf005

```
apt install -y python3 python3-pip git curl
git clone https://github.com/time-series-foundation-models/lag-llama/
cd lag-llama
pip install -r requirements.txt # Instala os pacotes necessários já descritos nesse arquivo
huggingface-cli download time-series-foundation-models/Lag-Llama lag-llama.ckpt --local-dir lag-llama
```

