## CSS 속성

### gap
본인이 아닌 자식들에게 인접한 자식들끼리 여백을 두도록 만들 수 있게한다.
> gap: 1.25rem;

### object-fit, object-postion
삽입된 이미지의 속성을 정한다. (배경으로 한다던지...)
https://ossam5.tistory.com/124

### outline-offset
border outline으로 하면 줄맞춤은 되지만 라인이 밖으로 삐져나와서 Box를 만들때 굉장히 지저분해 보인다. 이럴때 outline-offset의 음수값을 입력하면 border inline과 똑같은 효과를 누리면서 줄맞춤도 깨끗하게 된다.

### inset 속성
inset은 태그 요소의 위치를 결정하는 top, right, bottom, left의 축약 스타일 속성입니다. 즉 상하좌우를 각각의 css 속성으로 설정하지 않고 inset 하나만 사용하는 것이 가능합니다. 사실 inset을 사용하지 않더라도 top, right, bottom, left 등을 사용할 수 있겠습니다.

### isolate 속성
https://developer.mozilla.org/ko/play

## 선택자

### IS 선택자
같은 속성에 여러개의 요소를 한꺼번에 선택할 수 있다.
https://ui.toast.com/weekly-pick/ko_20210721


## 함수

### clamp
최소값과 최대값 범위내의 중간값을 선택한다.
