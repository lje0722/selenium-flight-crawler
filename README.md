# selenium-flight-crawler
___
<div align="center">
<h2>🛫 네이버 항공권 최저가 크롤링</h2>
네이버 항공권 최저가 자동 크롤링 프로그램입니다.<br> 
Selenium을 사용하였으며 프로그램 시작 전 출발 날짜 기준 몇 일을 자동크롤링 할지 repeat_day에 입력하고 <br>프로그램이 시작되면 출발 날짜와 체류기간을 입력합니다.
크롤링 결과는 코드 맨 아래 저장된 이름의 엑셀파일로 정리되어 저장됩니다.
</div>

## 개요
- 라이브러리: Selenium 
- 프로젝트 시기: 2024.11
- 개발 엔진 및 언어: Python & Jupyter Notebook



## 프로그램 설명
1. 프로그램이 시작하면서 출발날짜와 총 체류기간을 입력받습니다. Return 이후 돌아오는 날짜는 자동 계산!
2. 프로그램이 동작하며 최저가 태그가 붙은 항목의 항공사, 출발 도착 날짜와 시간 그리고 최종가격을 엑셀에 저장합니다.<br>
3. 단! 프로그램은 2024.11월을 기준으로 작성되었기 때문에 UI가 변경되거나 태그가 변경되면 동작에 에러가 발생할 수 있습니다.


## Client 정보
자동 크롤링 차단을 피하기 위해 프록시 서버와 클라이언트 컴퓨터 정보를 무작위로 선택하여 프로그램을 시작합니다. 프록시서버가 유효하지 않게 되거나 네이버 항공 태그나 UI가 변경될 경우 동작이 제한될 수 있습니다.

## 결과 








