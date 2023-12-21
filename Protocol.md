# 프로토콜이란?

## 정의
  - 프로토콜은 컴퓨터의 공통 언어로, 각 장치들이 주고받는 메시지의 양식과 규칙을 정해놓은 것이다.
    
    ```plaintext
    ex) 영어가 세계 공용어인것 처럼, 컴퓨터들이 서로 통신하기 위해서는 공용어인 프로토콜을 사용해야 한다
    ```
  - 네트워크로 연결된 장치들은 서로 다른 소프트웨어와 하드웨어를 사용하는 경우가 많기 때문에 반드시 프로토콜을 사용해서 통신해야한다

<br>

## 네트워크 프로토콜의 종류
  - OSI 7계층으로 분류한 네트워크 프로토콜 종류
    <img width="561" alt="image" src="https://github.com/Hwan0518/Network-Study/assets/108791919/1610e204-a853-4eeb-9a8e-f5dd8a24caf0">
    ```plaintext
    ex) FTP : 파일 전송 프로토콜
        HTTP : 하이퍼 텍스트 전송 프로토콜
        SMTP : 전자 우편 전송 프로토콜
        IP : 인터넷 프로토콜
        TCP : 전송 제어 프로토콜
    ```

<br>

## 프로토콜의 구성요소
<img width="548" alt="image" src="https://github.com/Hwan0518/Network-Study/assets/108791919/9728d385-543d-47b4-a8b6-fc1a261c29c4">


- Syntax (구문)
```plaintext
  - 데이터의 '형식(format)', '부호화(coding)' 등을 규정
  - 사람 언어의 문법이라 생각하면 됨
```
- Semantics (의미)
```plaintext
  - 효율적이고 정확한 정보 전송을 위한 '협조 사항'
  - 오류 관리를 위한 '제어 정보' 를 규정
  - 데이터의 각 부분이 무엇을 의미하는지를 정해둔 규칙이라 생각하면 됨
```
- Timing (시간)
```plaintext
  - 두 장치간의 '통신 속도', 메시지의 '순서 제어' 등을 규정
  - 어떤 데이터를 얼마나 빠르게, 어떤 순서로 보낼지를 정해둔 규칙이라 생각하면 됨
```

<br>


### Reference
- https://computer-science-student.tistory.com/377
- https://github.com/Hwan0518/Network-Study/blob/main/230815_%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%20%EA%B0%9C%EC%9A%94/%5BStudy%5D%20%EA%B9%80%EB%8F%99%ED%99%98.md
