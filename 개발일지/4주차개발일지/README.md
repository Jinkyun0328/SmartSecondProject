# SmartSecondProject
## 4주차개발일지
### 오류해결과정
github와 연결하면서 프로젝트에 오류가 발생했다.        
- 서버가 실행이 되지 않았다.        
![111](https://github.com/Jinkyun0328/SmartSecondProject/assets/123911778/d235e0b1-bf4a-45a0-b41d-984be1ebf9a0 align="right")        

Multiple Contexts have a path of "/MessageSystem"이 중복되어서 실행되지 않았다.        
servers -> tomcat -> module로 들어가서 Path를 변경하여 해결한다.        

- 서버를 다시 설치했는데 오류가 발생했다.        
![222](https://github.com/Jinkyun0328/SmartSecondProject/assets/123911778/6f49410f-5557-428e-a1de-1e69bcc4304b align="right")        
프로젝트 -> Properties -> Maven -> Project Fcets -> Runtimes -> 서버선택        

서버를 다시 설치하면 이전의 서버와 연결되어 있는 런타임을 새로운 서버로 변경해야한다.        

- 프로젝트를 새로 만들었는데 빨간줄이 생성되었다.        
![444](https://github.com/Jinkyun0328/SmartSecondProject/assets/123911778/9240d9d4-ae2c-400f-bb5f-4c96323d2d3f align="right")        
위의 문제가 발생했을 경우에는 Alt + F5 버튼을 눌러서 프로젝트를 새로고침한다.        


