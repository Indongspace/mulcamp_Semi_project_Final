# 개요
![20240328_100114](https://github.com/j2nhyeok/team_mini_project/assets/103464891/5a778afe-fd76-4ae1-82c9-4c970563add7)
### 분석 기간  </br>
2024-03-11 ~ 2024-03-28 (17일)
### 분석 배경 및 목적
현재 서울은 대한민국에서 가장 인구가 많은 도시이자 수도로, 시민 안전에 큰 관심을 가지고 있다. 그러나 인구밀도가 높아 한 번의 화재 사고로 인한 피해가 막심하다. 특히 화재로 인한 피해는 시간이 매우 중요한 골든타임에 달려 있다. 이를 위해 매년 소방차 통행로 환경을 개선하기 위한 예산이 투입되고 있지만, 여전히 출동 장애요인이 존재한다. 서울은 소방차 진입이 어려운 지역으로 알려져 있으며, 이러한 지역에는 비상소화장치조차 설치되지 않은 곳이 많다. 이 문제를 해결하기 위해 추가적인 비상소화장치함 설치 장소를 제안하여 화재로 인한 피해를 최소화하고자 한다.

### 해결과제 
<center>
<img src="https://github.com/j2nhyeok/Semi-project/assets/103464891/145e46e9-b8b7-4d95-976a-e4be9867a601" width="400" height="150"/></br>
</center></br>
서울시의 '골든타임 내 조기진압이 어려운 한계점'을 해결하기 위해, '비상소화장치'의 설치 위치를 제안하는 프로젝트를 진행한다. 이를 위해 서울시 내 주택화재 취약 지역을 분석하여 취약 지역을 선정하고, 해당 지역구에서 비상소화장치의 효용도가 높은 지역을 도출하여 설치를 제안한다.

### 기대효과 및 한계점
```
- 기존의 ‘화재취약지 선정기준’과 다른, 새로운 시각인 ‘주택지역중심’ 이라는 또 하나의 선정기준을 제공.
- 서울시 내 소방서/안전센터와 비상소화장치 위치에 대한 정보를 한 눈에 볼 수 있는 대시보드를 제작하여 소방시설 파악 수월.
- 프로젝트에 활용된 선정 기준과 분석 방식을 사용해 타 지역의 화재취약지에 대한 분석과 선정이 가능.

- 기술적 이용 간과: 소방예산, 소방시설 설치 및 관리에 들어가는 비용 등 재정에 대한 요소 고려 필요, 실제 비상소화장치 근처 거주민들은 공간의 차지로 불편함을 호소
- 데이터 품질 한계: 지역구 내의 동 별 데이터로 세분화된 범위의 데이터가 없어, 지역구 전체 내 적절한 위치를 직접 지도를 찾아가며 시간이 소요됨 
- 데이터 수집 한계: 더 다양한 데이터(시간에 따른 건물 내 거주 인원, 유동인구, 건물당 소방서 및 안전센터와의 거리 등)들을 취약지 선정과 입지 제안에 활용한다면 새로운 고려요소가 도입되어 현재보다 다양한 선정기준이 생성됨
```

### 결과

# 팀원 소개
<span style="color:#808080">자세한 역할은 PPT 발표 자료에서 확인하실 수 있습니다. </span>

🙋‍♀️[정주영(팀장)](https://github.com/Ju0s),
🙋‍♀️[김수현](https://github.com/suhyeon0325) 
🙋‍♀️[김영기](https://github.com/Y0un9Ki) 
🙋‍♀️[송인동](https://github.com/indongspace) 
🙋‍♀️[정소영](https://github.com/Jsoyoung) 
🙋‍♀️[최진혁](https://github.com/j2nhyeok)


# Tool
### 분석 환경 
- Programming Language : Python
- Editor : Google colab, Jupyter Notebook
### 주요 라이브러리

```
geopandas==0.14.3
plotly==5.20.0
streamlit==1.32.2
streamlit-folium==0.18.0
folium==0.16.0
jupyterlab==4.1.4
matplotlib==3.8.3
numpy==1.26.4
openpyxl==3.1.2
pandas==2.2.1
pyproj==3.6.1
scikit-learn==1.4.1.post1
scipy==1.12.0
seaborn==0.13.2
shapely==2.0.3
```

# 현장 답사
![20240328_112029](https://github.com/j2nhyeok/Semi-project/assets/103464891/daadf848-4468-4307-804f-20dde06e1cd4)


# 발표 자료
# 데모페이지 시연 영상

<details><summary> Django(김영기)
</summary>
[Django 대시보드 데모 영상: [유튜브에서 보기]](https://youtu.be/UrKuKw7LCUs?si=E40njPHtkqsuWSG8)
</details>

<details><summary> Streamlit(김수현)
</summary>
[Streamlit 대시보드 데모 영상: [유튜브에서 보기]](https://youtu.be/Y15JNbI---8?si=9U2TSQVvLB96yJF6)   

</details>

