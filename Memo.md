2019-11-21
*데이터문제해결및실습
# 클러스터링 할 수 있도록 하자! 
# 그룹으로 추천해주는게 훨씬 쉽다. 

# clustering 한 후에 aggregation(통합하다) methods를 사용해야 한다.
# Multiplicative은 많이 안 쓰이는 이유는 overflow, underflow가 발생한다. 
# 평균을 쓰는 것이 훨씬 좋다. 
# 실제 데이터에센 최고점 데이터가 있다.
# AV예제에선 4이상일 떄를 뽑았다.
# borda count 확인하기! 
# CR은 편균 평점이 높은지 낮은지 확인하는 것 
# MR은 비교 결과로 쓰이긴 쉽지만 영향력을 보면 좋다.
# graph theory
# google의 탄생배경인 알고리즘 : page rank algorithm 트위터 구조랑 비슷하다. 
# 얼마나 큰 노드를 나누는가 얼마나 많은 노드를 받았는가 
# 편차를 고려한다. AwM을 보고서 다수의 이용자가 만족할 수 있도록 한다.
# Least Misery는 negative한 평점을 받은 아이템을 빼버린다.
# Fa2 에서 최소값에서 편차* 특정 가중치를 빼준다.
# 가중치를 (1- 표준편차)로 해야 할 것입니다. 
# 시험에 나올 예정 

*데이터 시각화
# 빨간색 계속바다가 다른 거보면 녹색 
# 노란색은 조금 특이하다.
# 보색인 관계는 정말 잘 띈다.
# 색상의 표가 존재한다.
# Hue : 색상 
# vlaue : 밝기 Chroma : 채도
# 색을 느끼는 기준: 재질의 색깔 * 빛의 색깔
# Simultaneous Contrast : Bezold effect
# Spreading
# 색의 구분은 그 나라 언어가 어떻게 구성되는지에 따라 많이 달라진다. 
# Evolution of Basic Color Terms
# Hints for the colorist
'''
• Use only a few colors (~6 ideal) : 많이 쓰지 말아라
• Colors should be distinctive and named : 애매한 색깔은 되도록 쓰지 말기
• Strive for color harmony (natural colors?)
• Use cultural conventions; appreciate symbolism
• Beware of bad interactions (red/blue etc.)
• Get it right in black and white
• Respect the color blind
'''
# rainbow color는 되도록 쓰지 말 것 
# 정말 어렵다.
'''
Classing quantitative data
1. Equal interval (arithmetic progression)
2. Quantiles (recommended)
3. Standard deviation
4. Classification [Jenks’ “natural breaks”]
5. Equal area
6. Minimal length boundaries
7. Minimal gaps
'''
# http://colorbrewer2.org/#type=qualitative&scheme=Pastel2&n=6 사용해보기
# 가운데는 옅은 색으로 하는 것이 좋다.
# 진한 색이 더 많이 사용되어진다.