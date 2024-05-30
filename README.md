### Set up: 
```
python --verison
Python 3.11.7

pip install -r requirements.txt
```

### For Mac setup run the following command additionally:

```
brew install libomp
```

```
pip install --upgrade pip
pip install \
   --no-binary lightgbm \
   --config-settings=cmake.define.USE_OPENMP=OFF \
   'lightgbm>=4.0.0'
```

```
pip install requirements.txt
```
### Test Local:

```
jupyter lab

verify:
http://0.0.0.0:
```

```
open student-data-example.ipynb 
```
