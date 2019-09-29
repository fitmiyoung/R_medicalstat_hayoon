# R_medicalstat_hayoon
하윤 처방전 2019년 데이터 통계 분석

## 목표:
1. 문서로 받은 하윤의 처방전 DB화
2. 처방전 DB시각화
3. 시스템화 (파란색: 인풋데이터, 빨간색: 아웃풋 데이터)
  + 증상(질병기호)에 따라 처방된 약품 통계
  + 증상(질병기호)에 따라 처방되어질 약품 예측
  + 약품 정보로 호전되는 기간(투약 종료 시점) 예측

<br />
🤢 이슈: 

1. 하윤의 개인 정보(나이, 키, 몸무게)로 인해 하윤 나이대로만 정량화 할 수 있음.
2. 정성적인 데이터 증상을 정량 데이터 질병기호로 매칭해야만 사용할 수 있음. 
<br />
👩🏻‍🦰 이슈 해결 대안: 

국민관심질병통계 등 보건의료데이터 활용 (http://opendata.hira.or.kr/op/opc/olapMfrnIntrsIlnsInfo.do)

