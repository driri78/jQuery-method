# jQuery Effect Method

show() / hide() : display 속성 제어  
fadeIn() / fadeOut() / fadeTo() / fadeToggle()  
slideDown() / slideUp() / slideToggle()  
animate()

# 공통 파라미터

duration
기본값 400(0.4s), "slow", "fast", 1000 \* 5

show(duration) / hide(duration)

fadeIn(duration) / fadeOut(duration) / fadeTo(duration, opacity) / fadeToggle(duration)

slideDown(duration) / slideUp(duration) / slideToggle(duration)

hight(값) / width(값) => set  
hight() / width() => get

animate({css 객체}, duration, ease(timing function), callback)  
=> setInterval, for문 사용하여 여러번 쓰임  
// css keyframes 를 실행하는것과 같다  
// ease : 'swing'(생략하면 기본값), 'linear' 두가지 밖에 없음

callback  
// 파라미터로 전달된 함수  
// 특정 event가 일어나면 처리할 코드

# 주의

내부적으로 transition, keyframes을 사용하기 때문에  
개발자가 css값으로 transition을 사용하면 error
