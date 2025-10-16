# **탈모 진행 단계별 모니터링 시스템;**
## **두피와 머리카락 분석을 통한 추적 관리 및 예측 모델링**
&nbsp;
## **Ⅰ. 모델 개요**
### **`FUNCTION 1` : 탈모 상태 분류 (4개)**
&ensp;&ensp;✓&ensp;DL&ensp;&rarr;&ensp;<u>CNN</u>  
&ensp;&ensp;✓&ensp;MODEL&ensp;&rarr;&ensp;<u>EFFICIENTNET_V2_S</u>  
&ensp;&ensp;✓&ensp;경량화
### **`FUNCTION 2` : 두피 면적과 머리카락 면적의 비율**
&ensp;&ensp;✓&ensp;ML&ensp;&rarr;&ensp;<u>Color Segmentation</u>  
&ensp;&ensp;✓&ensp;MODEL&ensp;&rarr;&ensp;<u>K-MEANS CLUSTERING</u>
### **`FUNCTION 3` : 모공 하나 당 머리카락 개수**
&ensp;&ensp;✓&ensp;DL&ensp;&rarr;&ensp;<u>Object Detection</u>  
&ensp;&ensp;✓&ensp;MODEL&ensp;&rarr;&ensp;<u>YOLO 11N</u>  
&ensp;&ensp;✓&ensp;경량화
test
## **Ⅱ. 모델 구축**
#### **(FUNCTION 1) EFFICIENTNET_V2_S**
#### **(FUNCTION 2) K-MEANS CLUSTERING**
#### **(FUNCTION 3) YOLO 11N**
test
## **Ⅲ. (DL) 모델 경량화**
#### **(FUNCTION 1) EFFICIENTNET_V2_S**
#### **(FUNCTION 3) YOLO 11N**
test
## **Ⅳ. 모델 배포**
#### **1. 실시간 처리 방식 (BY Raspberry Pi)**
##### **1-1. FUNCTION 1 + FUNCTION 3**
##### **1-2. FUNCTION 2**
#### **2. 이미지 업로드 방식 (BY Flask)**
##### **2-1. FRONT-END**
##### **2-2. BACK-END**