## Summary
Face detection을 활용하여 성별 분류 시스템
훈련데이터 : 외국인 얼굴 80% 한국인 얼굴 20%


## openvino로 intel gpu활용
* 최신 cpu일 경우 pip install openvino(setupvars.bat 하지 않아도됨)
* 과거 cpu일 경우 과거 버전을 archive를 통해서 다운로드
  * call 경로 /setupvars.bat을 통해 활성화
https://storage.openvinotoolkit.org/repositories/openvino/packages/2024.1/windows/
 
## install
python version = 3.8
```bush
pip install ultralytics
pip install opencv-python
pip install openvino
```

