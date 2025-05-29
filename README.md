## Summary
Face detection을 활용하여 성별 분류 시스템
훈련데이터 : 외국인 얼굴 80% 한국인 얼굴 20%

## 환경
* 라떼판다 3 델타
* CPU : n5105
* GPU : UHD

## yolo11 model openvino version
* yolo11모델은 2024.05 버전 이후만 가능함.
* python version : 3.9
* https://github.com/openvinotoolkit/openvino/releases
* 2024.06 버전을 사용하였음.
```bush
conda install -c conda-forge openvino=2024.6.0
pip install openvino==2024.6.0
```

## openvino로 intel gpu활용
* 최신 cpu일 경우 pip install openvino(setupvars.bat 하지 않아도됨)
* 과거 cpu일 경우 과거 버전을 archive를 통해서 다운로드
  * call 경로 /setupvars.bat을 통해 활성화
https://storage.openvinotoolkit.org/repositories/openvino/packages/2024.1/windows/
 
## install
python version = 3.8
```bush
pip install openvino==2024.6.0
pip install ultralytics
```

