# share-price-prediction
본 repository에서는 [PyKrx](https://github.com/sharebook-kr/pykrx) 모듈을 사용하여 주가 정보를 scrappring 후, 주가를 예측하는 알고리즘 제작을 목표로 한다.

## 1. Environment setup

### 1.1 install python and packages
```bash
$ pyenv install 3.8.5
$ pip install -r requirements.txt
```

### 1.2 solve numpy runtime error
```bash
RuntimeError: Polyfit sanity test emitted a warning, most likely due to using a buggy Accelerate backend. If you compiled yourself, see site.cfg.example for information. Otherwise report this to the vendor that provided NumPy.
RankWarning: Polyfit may be poorly conditioned

$ pip unintsall numpy
$ brew install openblas
$ OPENBLAS="$(brew --prefix openblas)" pip install numpy
``` 

