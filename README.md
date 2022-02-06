# Solarstargram 

> ❤️‍🔥발생문제, 해결방법, 개념정리 노트   
>  Kotlin 안드로이드 앱 만들기 : 수강강좌 → [하울의 안드로이드 인스타그램 클론 만들기](https://www.inflearn.com/course/인스타그램만들기-안드로이드/dashboard)   
---
### 1. 첫번째 문제 : kotlin-android-extensions이 더이상 지원되지 않음.
- 해결방법 : View Binding 또는 findViewById()사용
+ 개념정리 : findViewById() 대신 View Binding을 사용하는 이유
---
### 2. 두번째 문제 : startActivityForResult()와 onActivityForResult() API가 더이상 지원되지 않음.
- 해결방법 : 새로 도입된 Activity Result API 사용
+ 개념정리 : 기존 방법과 차이점, 새로운 method의 구성요소 및 동작원리
 ++ 
* 공식문서 : https://developer.android.com/training/basics/intents/result?hl=ko#kotlin
  
  * 변경 전
```
    override fun onActivityResult(requestCode: Int, resultCode: Int, data: Intent?) {
        super.onActivityResult(requestCode, resultCode, data)
```
  * 변경 후
```
    override fun onActivityResult(requestCode: Int, resultCode: Int, data: Intent?) {
        super.onActivityResult(requestCode, resultCode, data)
```

