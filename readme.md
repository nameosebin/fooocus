# FOOCUS

## setup


```
git clone https://github.com/nameosebin/fooocus/
cd fooocus

pip install -r requirements_versions.txt
wget -P ./models/loras/ https://civitai.com/api/download/models/177674?token=<API_TOKEN> --content-disposition

apt-get update && apt-get install libgl1 -y

python entry_with_update.py --share --preset realistic --always-offload-from-vram
```
