##### Shakespeare's play
##### 셰익스피어 스타일의 문장생성  


###### Google Colaboratory에서 진행하기를 추천합니다.

  
##### Point

![444444444](https://user-images.githubusercontent.com/71945157/94942113-cc4ac580-0510-11eb-9744-a48f95d800b2.png)

```python
predictions = predictions / temperature
```

###### temperature 가 낮을수록 예측 후보중 정확도가 높은 선택지에 가중치를 부여합니다

||예측후보A|예측후보B|GAP|
|------|---|---|---|
|predictions|0.7|0.3||
|temperature=0.1|7|3| 4|
|temperature=1.0|0.7|0.3|0.4|
