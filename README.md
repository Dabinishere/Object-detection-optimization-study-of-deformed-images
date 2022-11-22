
# A Case Study of Object detection via Generated image Using deep learning model based on image generation
<br>
<div align="center">
    
   **[딥 러닝 기반 이미지 생성 모델을 활용한 객체 인식 사례 연구]**
  
</div>

![image2](https://user-images.githubusercontent.com/94797349/203092739-2f5f2daf-08a4-43e7-935c-6585cfd969d8.png)
<br><br>
<div align="center">
    
   Yolov5🚀의 취약점 검사를 위해 COCO val 2017의 동물 객체 중 8가지를 카테고리로, 툴은 DALL-E-2를 이용해 생성한 이미지를 데이터 셋으로 하여 정확도를 검사한다.
   도출된 취약점 개선을 위해 디노이징🚀(NAFNET), SR🚀(SRCNN)로 최적화 후 정확도 검사 연구를 진행한다.
  
</div>
<br>
    
# Tool
                       [<img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/>](https://www.python.org/)
  [<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=Python&logoColor=white"/>](https://openai.com/dall-e-2/)
  [<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=Python&logoColor=white"/></a>](https://colab.research.google.com/drive/1gjUVQBpd7Ib5NlojBwcZRh3B2MkRicc7#scrollTo=q2T8J68g11da)
  [<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Python&logoColor=white"/></a>](https://www.figma.com/file/XDfuWXEdcqPD4pNmuAuZx0/HI%3AM?node-id=25%3A548&t=SAizXbg7iZ7TVM0U-0)
  [<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=Python&logoColor=white"/></a>](https://developer.mozilla.org/ko/docs/Web/JavaScript)

<br>

### technology
<br>

> **Dalle-2**
> <br>[<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=Python&logoColor=white"/>](https://openai.com/dall-e-2/)

적대적 공격 사례에 활용되는 이미지들은 현실에 존재하는 이미지를 생성한 것이다. 그러므로 DALL-E-2를 활용하여 이미지를 생성할 때 작화 형식이 아닌 실제 현실과 유사한 사진 형식으로 이미지를 생성하기 위해 'A photo of'구문을 문장의 앞에 삽입하였다.
<br>

|한글|영어로 번역|DALL-E-2로 생성한 이미지|
|------|---|---|
|"냉장고를 열고 샌드위치를 꺼내는 소"|"a photo of a cow that opens the refrigerator and takes out a sandwich"|<img src = "https://user-images.githubusercontent.com/94797349/203352353-0eea3a28-0bfc-413b-89bb-a11486a88128.png" width="250" height="200"/>|
<br>

|giraffe|bear|elephant|cow|
|---|---|------|---|
|A photo of a giraffe that throws a discus in a truck|A photo of a bear sitting on a chair and eating a sandwich|A photo of a Elephant looking at the clock while putting flowers in the pot|A photo of a sheep truckload of apples and oranges with a salad and wine|
|<img src = "https://user-images.githubusercontent.com/94797349/203360905-13407716-f8ed-41a1-83bf-0474dc834214.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361010-a807b5c8-4bac-45c6-8590-4ced594eb644.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361123-f411c47e-a6c0-4901-9d89-be51a41e8cc4.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361198-d7638f1b-2cbe-4b88-b230-7fd2391c7c5f.png" width="150" height="150"/>|
|sheep|horse|dog|cat|
|A photo of a cow that opens the refrigerator and takes out a sandwich|A photo of a horse wearing sunglasses and lying on a sunbed under a pararol|A photo of a dog tried on shoes at a shoe store|A photo of a cat putting on lipstick in front of the mirror|
|<img src = "https://user-images.githubusercontent.com/94797349/203352353-0eea3a28-0bfc-413b-89bb-a11486a88128.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361292-128292fe-9502-4558-a7ea-9f5b26bc1351.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361371-7fbb1ea3-31c8-4cd4-9b44-12c73d85660c.png" width="150" height="150"/>|<img src = "https://user-images.githubusercontent.com/94797349/203361443-59c4029b-36c1-4903-9f55-4b497ecef3a9.png" width="150" height="150"/>|

> **Yolov5x**
> <br>: [YOLOv5](https://github.com/ultralytics/yolov5)
<br>

> **디노이징[NAFNET]**
<br>

> **SR[SRCNN]**
<br>


# WebSite HI:M  
🌟**HI:M**
<br>High quality:IMage<br>

> 연구 과정에서 사용한 디노이징과 SR을 활용한 화질개선 웹사이트
<div align="center">

  ![Component 1](https://user-images.githubusercontent.com/94797349/203244406-a1b74f7b-f5ea-491b-b125-9938304297d1.png)

</div>

🌟**Purpose**<br><br>
> 깔끔한 디자인의 화질 개선 웹 사이트 개발
<br> 일반 사용자: SNS 업로드, 리뷰 작성 등 고화질의 이미지를 필요로 하는 업무에 이용
<br> 데이터셋 구축: 데이터로 사용할 이미지 파일 화질 개선<br>

🌟**재홍 WebSite 링크**
<br><br><br>

## FrontEnd
      [<img src="https://user-images.githubusercontent.com/94797349/203263241-95cb7160-0a81-4bc7-ae12-0ad275a40b60.png" width="100" height="150"/>](https://www.figma.com/files/recent?fuid=1158726737653483793)               [<img src="https://user-images.githubusercontent.com/94797349/203263379-dab35c9f-8284-44dc-9a2f-e18d51c38a7d.png" width="120" height="150"/>](https://developer.mozilla.org/ko/docs/Web/CSS)               [<img src="https://user-images.githubusercontent.com/94797349/203263442-e8c75941-9733-4723-988d-fa0c116fa5c4.png" width="140" height="150"/>](https://developer.mozilla.org/ko/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

<br><br><br>

## BackEnd
                                                            
                                                            [<img src="https://user-images.githubusercontent.com/94797349/203263564-9b1e63ae-d850-4937-b5af-be9811c3a7a3.png" width="120" height="150"/>](https://developer.mozilla.org/ko/docs/Web/JavaScript)
  
  

# conference

  > 회의록 : [회의록 DRIVE](https://docs.google.com/document/d/1fIRLpuA7V0Jb0l6fWg8KfU0ae6wXg9rNU_Z_M0-um4E/edit?usp=sharing)

<br>
