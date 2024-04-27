#FOOCUS

##setup


```
git clone https://github.com/lllyasviel/Fooocus.git
cd Fooocus
python3 -m venv fooocus_env
source fooocus_env/bin/activate
pip install -r requirements_versions.txt
wget -P ./models/loras/ https://civitai.com/api/download/models/177674?token=<API_TOKEN> --content-disposition
apt-get update && apt-get install libgl1

python entry_with_update.py 
```

For libgen.so
