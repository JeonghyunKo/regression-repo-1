# 제주도 대중교통 이용 관광객 예측 프로젝트
https://images.unsplash.com/photo-1609766418204-94aae0ecfdfc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1780&q=80![image](https://user-images.githubusercontent.com/80465347/119298247-991f9700-bc97-11eb-8cf1-516e1a4e6400.png)

제주도를 찾는 관광객들이 선택하는 주요 교통수단은 단연 렌트카이지만, (특히 코로나 19의 여파로) 제주도가 점점 더 각광받는 관광지로 부상하면서 대중교통의 이용 또한 증가하고 있습니다. 
이에 대중교통을 이용하는 관광객의 수를 예측하여 관광지 주변 상권이나 Public Mobile 업체들이 활용할 수 있는 데이터를 만들고자 하였습니다. 

## Getting Started / 어떻게 시작하나요?

이 곳에서 설치에 관련된 이야기를 해주시면 좋습니다.

### Prerequisites / 선행 조건

아래 사항들이 설치가 되어있어야 합니다.

```
pip install pydeck
```

### Installing / 설치

아래 사항들로 현 프로젝트에 관한 모듈들을 설치할 수 있습니다.

```
import JejuRegion as JR
```

## File list 

-  JejuRegion.py : 권역 그룹핑을 위한 모듈 
-  jeju_datahub_api : 제주데이터허브 API 이용하기 
-  jeju_visualization_map : pydeck을 이용한 제주도 지역별 버스 이용량 시각화  
-  df_regression.csv : regression 용 데이터프레임 파일
-  jeju_clustering.ipynb : 버스 이용객을 대상으로 한 kmeans clustering
-  jeju_regression_part2.ipynb : 회귀분석 


## Built With / 누구랑 만들었나요?

* [정현](https://github.com/JeonghyunKo) - 파이덱 시각화 / 회귀분석 / 다스크
* [재훈](Link) - ## please write here


## License / 라이센스

This project is licensed under the MIT License - see the [LICENSE.md](https://gist.github.com/PurpleBooth/LICENSE.md) file for details / 이 프로젝트는 MIT 라이센스로 라이센스가 부여되어 있습니다. 자세한 내용은 LICENSE.md 파일을 참고하세요.

## Acknowledgments / 감사의 말

* [Flycode77](https://github.com/FLY-CODE77) /  부족한 질문에도 항상 성실하게 알려주셔서 감사드립니다.  
* [Radajin](https://github.com/radajin) / DASK-KING
* 제주데이터허브, 제주관광협회 / 갑작스러웠던 요청임에도 흔쾌히 데이터를 제공해주셔서 감사드립니다. 

* and [PinkWink](https://github.com/PinkWink) / Kmeans Clustering 제안으로 꽉 막혀있던 프로젝트의 돌파구를 제시하셨습니다.  
