# BIS

버스정보시스템입니다
ajax와 css, html, javascript를 이용하였습니다.
만약 버스 도착 정보를 알고 싶으시다면 이걸 이용해보시길 바랍니다.

![image](https://github.com/jdi512/BIS/assets/156891813/cafb84e9-8c41-4b10-b9b4-3686df0da25b)

ajax - 공공데이터포털(http://data.go.kr)에서 버스 정류장 정보/도착 정보/기상정보/도착 예정 버스 자료를 받을 때(방식은 json)  (단, 도로명주소와 구주소는 kakaoapi를 통해 추출)
css - 해당 글자의 폰트(neo 둥근모꼴)와 배경색, 글자 크기, 시계의 ":" blink할 때 (style)
html(div) - 도착 버스가 일정 이상일 때 5개씩 나눌 때 쓰였음
javascript - 시간을 나타날 떄(setinterval)와 위 경도 -> x,y 변환시와 위, 경도르 gps로 받을 때 
