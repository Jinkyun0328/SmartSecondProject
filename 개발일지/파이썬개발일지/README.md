# SmartSecondProject
## 1. 자바에서 파이썬 실행하기
프로젝트에서 사용할 객체검출 프로그램인 Yolo는 파이썬 기반의 프로그램이다.
자바에서 사용할 수 있도록 API를 가져오거나 파이썬 파일을 자바 프로젝트에서 실행할 수 있어야 한다.

### 1. processbuilder 사용하기
![images1](https://user-images.githubusercontent.com/123911778/280884490-0696c251-ad1c-407d-893b-a65a72bda32a.PNG)
위의 코드를 사용하면 파이썬 파일을 읽어와서 자바에서 실행할 수 있다.

#### 문제점
- processbuilder의 주소는 작업주소에 해당하는데 현재 작업주소가 바탕화면으로 되어있어서
  바탕화면에서부터 주소를 입력해주어야 한다. 이 코드를 실행하면서 python 파일을 같은 폴더에 놓았으나
  hello.py가 정상적으로 실행되지 않았다.

- opencv같이 설치가 필요한 파일같은 경우 실행되지 않았다.

#### 실행결과
![images2](https://user-images.githubusercontent.com/123911778/280884484-f4631e32-dc0e-488f-9469-2951ad92fa22.PNG)
