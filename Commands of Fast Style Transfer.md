## ����
fast-style-transfer �� ���� ��ɾ� �Ұ��Դϴ�.

## ���� ���
�ڵ带 �����Ϸ���
- �ڵ带 �ٿ�޾ƾ� �մϴ�.
- ��ġ�ؾ� �ϴ� ������ ��� ��ġ�Ǿ� �־�� �մϴ�.
- �ڼ��� ������ �� [��ũ](https://github.com/ShafeenTejani/fast-style-transfer)�� �ֽ��ϴ�.
1. �ʿ��� ��ġ������ ��� ��ġ�մϴ�.
2. �� ��ũ���� clone or download�� �ٿ�ε� �մϴ�.
3. ��� ������Ʈ(cmd)�� ������ �������� �����մϴ�.
4. ��ɾ� ���� ����� �����Ͽ� ��ɾ �����մϴ�.

## ��ɾ� ���� ���
- Ư�� ��Ÿ���� ��Ʈ��ũ �н���Ű��</br>
  �⺻ ��ɾ�� ���� ������ �����ϴ�.</br>
  ```python train_network.py --style <style image> --train-path <path to training images> --save-path <directory to save network>```</br>
  �� ��ɾ��� ���ڴ� ������ �����ϴ�.
  ```
  train_network.py            �ٿ���� �����Դϴ�. cmd���� ������ ���� ��α����� ��Ȯ�� ����� �մϴ�.
  --style                     ��Ÿ�� ������ �����ϱ� ���� �÷����Դϴ�.
  <style image>               ��Ÿ�Ϸ� ������ �̹��� �����Դϴ�. ��ο� �Ű��� �մϴ�.
  --train-path                �н��� ������ ����Դϴ�.
  <path to training images>   �н��� ������ �̹����� �ִ� ����Դϴ�.
  --save-path                 �н��� �Ϸ�� network�� �����ϱ� ���� �÷����Դϴ�.
  <directory to save network> �н��� �Ϸ�� network�� �����ϱ� ���� ����Դϴ�.
  ```
  �߰����� �÷��׷� �ɼ��� ���ϰ� ������ �� �ֽ��ϴ�. �������� ������ defalut ������ �����˴ϴ�.
  ```
  --epochs          NUM_EPOCHS=5          epoch�� �����մϴ�. 
  --batch-size      BATCH_SIZE=4          batch-size�� �����մϴ�.
  --learning-rate   LEARNING_RATE = 1e-3  learnig rate�� �����մϴ�.
  --content-weight  CONTENT_WEIGHT = 1    content-weight�� �����մϴ�.
  --style-weight    STYLE_WEIGHT = 5      style-wight�� �����մϴ�.
  --tv-weight       TV_WEIGHT = 1e-6      tv-weight�� �����մϴ�.
  ```
- GPU ����ϱ�
  GPU�� �̿��Ͽ� �н��� �����Ϸ��� ���� �÷��׸� ����մϴ�.</br>
  ```--use-gpu```
- �н��� ��Ʈ��ũ�� ���ο� �����͸� ��ȯ(�ռ�)�ϱ�
  �⺻ ��ɾ�� ���� ������ �����ϴ�.</br>
  ```python stylize_image.py --content <content image> --network-path <network directory> --output-path <output filename>```
  �� ��ɾ��� ���ڴ� ������ �����ϴ�.
  ```
  python              python ����� �����մϴ�.
  stylize_image.py    ���̽� ������ �����մϴ�. ��ο� �����ؾ� �մϴ�.
  --content           ��ȯ�� ������ �����ϴ� �÷��� �Դϴ�.
  <content image>     ��ȯ�� ���� ���� �Դϴ�.(source)
  --network-path      �н���Ų ��Ʈ��ũ�Դϴ�.
  <network directory> �н��� ��Ʈ��ũ�� ����Դϴ�.
  --output-path       ��ȯ�� ������ ��θ� �����ϴ� �÷����Դϴ�.
  <output filename>   ��ȯ�� ������ ����Դϴ�.(dest)
  ```
  
  ## ����
  �� �ڼ��� ������ [����](https://github.com/ShafeenTejani/fast-style-transfer/blob/master/README.md)���� Ȯ���� �� �ֽ��ϴ�.
  
  