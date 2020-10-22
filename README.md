
* Region 82   
가장 큰 Mask, Prediction Scale 을 이용하는 레이어이지만 작은 객체를 예측 할 수 있음   
* Region 94   
중간 단계 Mask, Prediction Scale    
* Region 106   
가장 작은 Mask, Prediction Scale 을 이용하는 레이어이지만 마스크가 작을 수록 큰 객체 예측 가능   
* Avg IOU    
현재의 subdivision에서 이미지의 평균 IoU   
실제 GT와 예측된 bbox의 교차율을 뜻함   
1에 가까울 수록 좋음   
* Class : 1에 가까운 값일 수록 학습이 잘 되고 있다는 것   
* No Obj : 값이 0이 아닌 작은 값이어야 함   
* .5R : recall/conut    
* .75R : 0.000000   
* count    
현재 subdivision 이미지들에서 positive sample 들을 포함한 이미지의 수    

Ref : https://eehoeskrap.tistory.com/370
