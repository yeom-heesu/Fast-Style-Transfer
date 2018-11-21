## 개요
fast-style-transfer 에 대한 명령어 소개입니다.

## 실행 방법
코드를 실행하려면
- 코드를 다운받아야 합니다.
- 설치해야 하는 파일은 모두 설치되어 있어야 합니다.
- 자세한 사항은 이 [링크](https://github.com/ShafeenTejani/fast-style-transfer)에 있습니다.
1. 필요한 설치파일을 모두 설치합니다.
2. 위 링크에서 clone or download로 다운로드 합니다.
3. 명령 프롬프트(cmd)를 관리자 권한으로 실행합니다.
4. 명령어 실행 방법을 참조하여 명령어를 실행합니다.

## 명령어 실행 방법
- 특정 스타일의 네트워크 학습시키기</br>
  기본 명령어는 다음 형식을 가집니다.</br>
  ```python train_network.py --style <style image> --train-path <path to training images> --save-path <directory to save network>```</br>
  위 명령어의 인자는 다음과 같습니다.
  ```
  train_network.py            다운받은 파일입니다. cmd에서 실행할 때는 경로까지도 명확히 적어야 합니다.
  --style                     스타일 파일을 지정하기 위한 플래그입니다.
  <style image>               스타일로 지정할 이미지 파일입니다. 경로에 신경써야 합니다.
  --train-path                학습을 진행할 경로입니다.
  <path to training images>   학습을 진행할 이미지가 있는 경로입니다.
  --save-path                 학습이 완료된 network를 저장하기 위한 플래그입니다.
  <directory to save network> 학습이 완료된 network를 저장하기 위한 경로입니다.
  ```
  추가적인 플래그로 옵션을 상세하게 설정할 수 있습니다. 설정하지 않으면 defalut 값으로 설정됩니다.
  ```
  --epochs          NUM_EPOCHS=5          epoch를 조절합니다. 
  --batch-size      BATCH_SIZE=4          batch-size를 조절합니다.
  --learning-rate   LEARNING_RATE = 1e-3  learnig rate를 조절합니다.
  --content-weight  CONTENT_WEIGHT = 1    content-weight를 조절합니다.
  --style-weight    STYLE_WEIGHT = 5      style-wight를 조절합니다.
  --tv-weight       TV_WEIGHT = 1e-6      tv-weight를 조절합니다.
  ```
- GPU 사용하기
  GPU를 이용하여 학습을 진행하려면 다음 플래그를 사용합니다.</br>
  ```--use-gpu```
- 학습된 네트워크로 새로운 데이터를 변환(합성)하기
  기본 명령어는 다음 형식을 가집니다.</br>
  ```python stylize_image.py --content <content image> --network-path <network directory> --output-path <output filename>```
  위 명령어의 인자는 다음과 같습니다.
  ```
  python              python 명령을 실행합니다.
  stylize_image.py    파이썬 파일을 실행합니다. 경로에 유의해야 합니다.
  --content           변환할 파일을 지정하는 플래그 입니다.
  <content image>     변환할 원본 파일 입니다.(source)
  --network-path      학습시킨 네트워크입니다.
  <network directory> 학습된 네트워크의 경로입니다.
  --output-path       변환된 파일의 경로를 지정하는 플래그입니다.
  <output filename>   변환된 파일의 경로입니다.(dest)
  ```
  
  ## 참조
  더 자세한 사항은 [여기](https://github.com/ShafeenTejani/fast-style-transfer/blob/master/README.md)에서 확인할 수 있습니다.
  
  