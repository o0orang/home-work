# 4차 과제 제출

## 결과
![이미지](/image_final.png)

## 마크업 코드, 설명

### html 

```
div.gridBox
    h1.new /*새소식*/
    a.view /*더보기*/
    div.hr
    figure.image01
     img
     figcaption /*W3C 리뉴얼*/
    div.text01
     h2
     p.text02
     p.text03
```
### css
- display:grid 적용
- grid-templage areas:
new 1열 3행, view 1열 3행
hr 1열 6행
image01 2열 4행, text02 4열 4행 적용
- 각 클래스에 gird-area 적용
- hr 태그를 쓰려고 했으나 잘 적용이 되지 않아 div 태그에 height: 1px;설정하여 해결, linear-gradient로 그라데이션 줌
