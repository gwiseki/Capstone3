# MyApplication
![ic_launcher](app/src/main/res/mipmap-xxxhdpi/ic_launcher.png)  
테스트용 앱입니다.
## How To Build
* 빌드하려면 Google Maps 키를 발급받아야 합니다!
다음과 같은 양식으로 Google Maps 안드로이드 앱 키 값을 입력하여 ./app/src/main/res/values/SecureKey.xml 파일을 생성 후 빌드
```xml
<resources>
    <string name="GoogleMapSecureKey">(Your Google Map API Key)</string>
</resources>
```
Firebase 설정에서 SHA 인증서를 등록해야 로그인 API가 작동함.\
SHA-1값 확인 방법: https://snowdeer.github.io/android/2017/08/21/android-studio-debug-sha1/
