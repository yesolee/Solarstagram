# Solarstargram 

> โค๏ธโ๐ฅ๋ฐ์๋ฌธ์ , ํด๊ฒฐ๋ฐฉ๋ฒ, ๊ฐ๋์ ๋ฆฌ ๋ธํธ   
>  Kotlin ์๋๋ก์ด๋ ์ฑ ๋ง๋ค๊ธฐ : ์๊ฐ๊ฐ์ข โ [ํ์ธ์ ์๋๋ก์ด๋ ์ธ์คํ๊ทธ๋จ ํด๋ก  ๋ง๋ค๊ธฐ](https://www.inflearn.com/course/์ธ์คํ๊ทธ๋จ๋ง๋ค๊ธฐ-์๋๋ก์ด๋/dashboard)   
---
### 1. ์ฒซ๋ฒ์งธ ๋ฌธ์  : kotlin-android-extensions์ด ๋์ด์ ์ง์๋์ง ์์.
- ํด๊ฒฐ๋ฐฉ๋ฒ : View Binding ๋๋ findViewById()์ฌ์ฉ
+ ๊ฐ๋์ ๋ฆฌ : findViewById() ๋์  View Binding์ ์ฌ์ฉํ๋ ์ด์ 
---
### 2. ๋๋ฒ์งธ ๋ฌธ์  : startActivityForResult()์ onActivityForResult() API๊ฐ ๋์ด์ ์ง์๋์ง ์์.
- ํด๊ฒฐ๋ฐฉ๋ฒ : ์๋ก ๋์๋ Activity Result API ์ฌ์ฉ
+ ๊ฐ๋์ ๋ฆฌ : ๊ธฐ์กด ๋ฐฉ๋ฒ๊ณผ ์ฐจ์ด์ , ์๋ก์ด method์ ๊ตฌ์ฑ์์ ๋ฐ ๋์์๋ฆฌ
 ++ 
* ๊ณต์๋ฌธ์ : https://developer.android.com/training/basics/intents/result?hl=ko#kotlin
  
  * ๋ณ๊ฒฝ ์ 
```
    override fun onActivityResult(requestCode: Int, resultCode: Int, data: Intent?) {
        super.onActivityResult(requestCode, resultCode, data)
```
  * ๋ณ๊ฒฝ ํ
```
    override fun onActivityResult(requestCode: Int, resultCode: Int, data: Intent?) {
        super.onActivityResult(requestCode, resultCode, data)
```

