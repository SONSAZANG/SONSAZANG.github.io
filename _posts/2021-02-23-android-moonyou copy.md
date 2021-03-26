---
layout: post
title: 2021-02-23
category: 공부 기록
tag: [Android, SDK, firebase, firestore]
---

Android - SDK location not found 오류 해결
moonyou - DB연동부분

# Android - SDK location not found

SDK location not found. Define location with an ANDROID_SDK_ROOT environment variable or by setting the sdk.dir path in your project's local properties file at '~/android/local.properties'.<bt>
원인 -> SDK 위치를 찾을 수 없는 것이 문제의 원인<bt>
해결 -> local.properties 파일에 경로 추가<bt>
For windows users<br>
﹒sdk.dir = sdk.dir=C\:\\Users\\UserName\\AppData\\Local\\Android\\sdk<br>
For Mac users<br>
﹒sdk.dir = /Users/USERNAME/Library/Android/sdk<br>
<br>
출처: https://eso0609.tistory.com/92 [엄코딩의 개발 일지]

# moonyou - DB 

Firebase = NoSql<br>
db를 위해서 Firestore 사용 필요<br>
Firestore 공부 필요<br>
[링크1](https://wooastory.tistory.com/119)<br>
[링크2](https://youtube.com/playlist?list=PLG9ohJAOA2PAYBb6rM7pq9Tip9QS2x2_3)<br>

