# Visualization

# Life Expectancy: 데이터 분석 및 시각화
목표 : 기대수명에 영향을 끼치는 주요 요인들에 대한 확인

## Index
1. 컬럼 소개 및 주요 요인 설명 
2. 패키지 임포트 및 데이터 로드
3. 데이터 전처리
4. 기대수명에 영향을 끼치는 요인 분석
5. 시각화
6. 선진국, 개발도상국으로 나눠 차이점 비교
7. GDP 상위 10개국과 하위 10개국의 기대수명과 상관관계가 높은 변수들에 대한 막대 그래프
8. 결론
* 별첨 : 세계지도 및 산점도

* ## 1. 컬럼 소개 및 주요 요인 설명

 - Country : 국가
 - Year : 연도
 - Status : 선진국 혹은 개발도상국
 - Life expectancy : 기대수명
 - Adult Mortality : 남녀 모두의 성인 사망률(인구 1000명당 15세에서 60세 사이에 사망할 확률)
 - infant deaths : 인구 1000명당 영아 사망자 수
 - Alcohol : 1인당 알코올 소비량
 - percentage expenditure : 1인당 국내총생산(%)에서 보건에 대한 지출
 - Hepatitis B : B형 간염
 - Measles : 홍역 - 인구 1000명당 보고된 환자 수
 - BMI : 전체 인구의 평균 체질량 지수
 - under-five deaths : 인구 1000명당 5세 이하 사망자 수
 - Polio : 만 1세 소아마비(Pol3) 예방접종 적용범위(%)
 - Total expenditure : 총 정부지출에서 보건에 대한 일반 정부지출(%)
 - Diphtheria : 만 1세의 디프테리아 파상풍 톡소이드 및 백일해(DTP3) 면역 적용 범위(%)
 - HIV/AIDS : 에이즈/후천선면역결핍증, 출생아 1,000명당 사망자 수 (0-4세)
 - GDP : 1인당 국내총생산(USD)
 - Population : 인구
 - thinness 1-19 years : 10~19세 아동·청소년의 마른 체형 유병률(%)
 - thinness 5-9 years :  5~9세 아동·청소년의 마른 체형 유병률(%)
 - Income composition of resources : 자원의 소득구성 측면에서의 인적개발지수(지수 0~1)
 - Schooling : 교육 연수(년)
