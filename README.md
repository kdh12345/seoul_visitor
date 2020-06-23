# seoul_visitor
출처: 서울시 열린데이터 광장

http://data.seoul.go.kr/dataList/datasetList.do

국적별 외국인 방문객 통계데이터를 바탕으로 데이터를 정제한 뒤 전체 방문객, 남성방문객, 여성방문객, 승무원 방문객을 대륙별로 분석하여 scatter그래프를 이용하여 시각화 하였습니다.

Applied Machine Learning 적용
그 중에서 cikit-learn package을 이용하여
The k-Nearest Neighbor(k-NN) Algorithm 머신러닝 알고리즘 적용하였습니다.

X축에 '남성인원','여성인원','승무원인원'
Y축에 'label'로 설정하여 값을 입력하여 해당 관광객이 어디 출신인지 예측하는 코드를 구현하였습니다.

