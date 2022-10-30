# Resume
* Intro

  HTML/CSS Resume

<br>
<br>

* Frame

![이력서프레임](https://user-images.githubusercontent.com/65724413/190192431-600a9350-4052-49b4-a7eb-895b6564f357.png)

<br>
<br>

* 제작과정

  2022.09.12<br>

  이력서 형식 작성을 위한 프레임 구성 및 넣을 내용 구상

  <br><br>

  2022.09.13<br>

  top~leftSide(contactInfo ~ languages) 작업

  <br><br>

  2022.09.14<br>

  leftSide(interest ~ essential skills) 작업

  <br><br>

  2022.09.15<br>

  검토 및 수정 github에 올리기

  <br><br>

* review

  pdf나 다른 형식으로도 이력서를 작성하겠지만, 한 번 마크업언어로 이력서를 구현해보고 싶어서 만들어 보았다. <br>

  아직까지는 실력이 그리 좋지 못해, 전반적으로 단순하다고 생각했다.<br>

  증명사진을 넣는 과정에서 레이아웃을 맞추는데 조금 고생을 했다. <br>

  CSS 의 스타일중 `aspecto-ratio`와 `object-fit` 요소를 써보았는데, `aspecto-ratio`로 먼저 사진을 담을 박스의 크기를 너비와 1대1비율로 맞추고  <br>

  이미지 속성에 `object-fit` 속성을 이용하여 박스 크기에 맞게 `cover`를 값으로 설정하니 깔끔하게 구현되었다. <br>

  개인적으로는 좌우의 줄 높이를 같게 해서 깔끔한 구성을 만들려했으나, 각 내용마다 사용하는 길이가 재각각이라 어쩔 수 없이 구체적인 px을 지정하지 않고 `min-height,width`속성을 사용하고 자식요소도 상속(`100%`)으로 상당부분 처리했다. <br>

  `flex`,`grid`를 사용하니 컨텐츠들을 정렬시키는 것이 생각보다 쉬웠다.(전체적인 구조가 단순한 것도 한 몫..) <br>

  

  
