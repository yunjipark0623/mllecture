# 매일 설문
https://docs.google.com/forms/d/e/1FAIpQLSdpNqMkiQLPf9_uGq7Jel2kxINxL-RNEGO9lHIxZlTXSCSxcA/viewform?usp=pp_url

# 190423
w(가중치(신경세포) = w - α(반영 비율) * h(기울기)  

E(오류함수) = (w * x - y)^2 (y는 기울기, x는 입력), (입력이 몇 번이냐에 따라 출력의 갯수가 정해진다)    
입력 x_1과 기울기 h_1에 대한 오류E_1, 입력 x_2와 기울기 h_2에 대한 오류 E_2,,,이렇게 입력의 갯수만큼 E들의 값을 구한 다음 E값들을 다 합치고 입력의 갯수 N으로 나눠서 평균 E(msE)를 구한다. -> 따라서, 입력이 몇 만개여도 그에 대한 오류(E)는 하나이다.  
또, x와 y는 상수이고 w_1만 변수이다. 이 w_1에 대한 E를 구한다음 w_1값을 조금 더 좋게 변형해서 w_2를 만드는 것이다. 

h = w * x  
