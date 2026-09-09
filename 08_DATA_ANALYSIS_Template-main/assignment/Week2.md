# 데이터분석 2주차 정규과제

📌데이터분석 정규과제는 매주 정해진 분량의 『*혼자 공부하는 데이터 분석 with 파이썬*』 을 읽고 학습하는 것입니다. 이번 주는 아래의 **DataAnalysis_2nd_TIL**에 나열된 분량을 읽고 공부하시면 됩니다.

아래의 문제를 풀어보며 학습 내용을 점검하세요. 문제를 해결하는 과정에서 개념을 스스로 정리하고, 필요한 경우 제시된 강의를 참고하여 보완하는 것이 좋습니다.

<!-- 강의 링크는 아래와 같습니다.
https://www.youtube.com/watch?v=s_-VvTLb3gs&list=PLVsNizTWUw7FGzSRCkQrPEEe-ljVXgS7k&index=4
https://www.youtube.com/watch?v=Il6L8OtNFpc&list=PLVsNizTWUw7FGzSRCkQrPEEe-ljVXgS7k&index=5
-->


## DataAnalysis_2nd_TIL

### 2장 데이터 수집하기
#### 01. API 사용하기
#### 02. 웹 스크래핑 사용하기


## Study Schedule

| 주차  | 공부 범위     | 완료 여부 |
| ----- | ------------- | --------- |
| 1주차 | p.24~81    | ✅         |
| 2주차 | p.84~151   | ✅         |
| 3주차 | p.154~219  | 🍽️         |
| 4주차 | p.222~279 | 🍽️         |
| 5주차 | p.282~325 | 🍽️         |
| 6주차 | p.328~379 | 🍽️         |
| 7주차 | p.382~430 | 🍽️         |

<br>

<!-- 여기까진 그대로 둬 주세요-->


# 1️⃣ 개념 정리 

## 01. API 사용하기

1. **API**(Application Programming Interface)는 프로그램 간 데이터를 전달하기 위해 정한 규칙이다. 수동으로 데이터를 받는 방법은 매주, 매일 반복되는 작업에선 부적절한데, 이런 경우 공개 API를 사용하면 데이터 수집 과정을 자동화할 수 있다.
2. **HTTP**(Hyper Text Transfer Protocol)는 웹에서 데이터를 주고받기 위한 통신 규약(Protocol)이다. 이를테면 웹 페이지, 이미지 등을 받아 웹 브라우저에 나타내는 데 HTTP를 활용한다. 그래서 웹 브라우저로 접속하는 URL 주소는 모두 http 혹은 https(보안이 강화됨)으로 시작한다. 핵심은 HTTP를 활용해 API를 만드는 것이 웹 기반 API라는 것이다.
<img width="254" height="68" alt="image" src="https://github.com/user-attachments/assets/80fcfa11-ad25-46de-b3d9-c90c5fd41f0c" />

<img width="251" height="65" alt="image" src="https://github.com/user-attachments/assets/68452d80-7956-4025-8f3d-f3320411bdaf" />

3. 웹 기반 API에서 HTML 대신 CSV, JSON, XML(이들 모두 웹 기반 API가 데이터를 전달하는 형태이다)을 선호하는 것은 HTML 소스의 구조가 복잡하기 때문이다. 단, CSV는 코드가 복잡하여 읽기 힘들다. 코드가 복잡해질수록 오류 발생 확률이 높아지고, 오류를 찾기 위해 데이터를 확인할 때도 이해하기 어려워진다.
3. **JSON**(Javascript Object Notation)은 근래에 범용적으로 많이 사용되는 데이터 전달 포맷이다. 자바스크립트는 물론 웹 기반 API에서도 대중화되어 있다. JSON의 장점은 HTML이나 XML보나 사람이 읽기 편하고 간단하게 파이썬 객체로 변환할 수 있다는 점이다.
4. **XML**(eXtensible Markup Language)은 JSON보다 다소 장황하지만 사람이 이해하기 쉬운 구조적인 포맷을 제공한다. 파이썬에서는 기본으로 제공되는 xml 패키기를 사용하여 XML 문서에 있는 element를 탐색할 수 있고, Pandas의 경우 read_xml() 함수를 사용하여 데이터프레임으로 바꿀 수 있다.

<img width="407" height="202" alt="image" src="https://github.com/user-attachments/assets/1be158c0-7a34-4c93-9979-5842dc43a332" />


## 02.웹 스크래핑 사용하기

<!-- 새롭게 배운 내용을 자유롭게 정리해주세요.-->


# 2️⃣ 수행 인증

<!-- 교재에서 안내된 과정을 직접 실행해본 뒤, 진행 결과가 보이도록 4~6장의 스크린샷을 캡처하여 아래에 첨부해주세요.-->



<br>
<br>

# 3️⃣ 확인 문제

## 문제 1.

> **🧚Q. 다음 중 BeautifulSoup 외에 웹 스크래핑에 사용할 수 있는 파이썬 패키지로 가장 적절한 것은 무엇인가요?**

```
1️⃣ NumPy  
2️⃣ Scrapy  
3️⃣ Matplotlib  
4️⃣ Scikit-learn  
```

```
여기에 선택한 답과 그 이유를 간단히 서술해주세요!
```



### 🎉 수고하셨습니다.
