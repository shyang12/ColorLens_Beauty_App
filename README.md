# ColorLens_Beauty_App
## ▶ 안드로이드 스튜디오 뷰티앱 만들기 (Kotlin)
 
 - 안드로이드 스튜디오에서 Kotlin을 기반으로 뷰티앱(컬러 렌즈)을 구현하는 프로젝트

`DataBinding` `Firebase` `firebase-ml-vision` `firebase-ml-vision-face-model` `camera`

## 1. Co-Development Environment   
### 1. 1 Environments
- Windows 10
- Android Studio / Kotlin, Java
- Firebase
- GitHub

### 1. 2 Implement
- 카메라를 이용하여 눈 색 변경등 필터 적용
- Bitmap을 통해 위치 조정
- GrapicOverlay를 사용하여 drawble에 저장된 렌즈가 눈을 따라가도록 설정
- 눈 위치 설정

## 2. Project Architecture   
```bash
├── main
│   ├── MainActivity.kt
│   ├── GraphicOverlay.java
│   ├── FaceGraphic.kt
│   └── Util.kt
├── ui
│   ├── layout
│   │   └── activity_main.xml
```

## 3. Firebase   
### 3.1  firebase-ml-vision

### 3.2  firebase-ml-vision-face-model

## 4. Result
- 렌즈 적용 카메라 화면 결과

![KakaoTalk_20240510_212712990](https://github.com/shyang12/ColorLens_Beauty_App/assets/85710913/dc981de6-2297-4335-b7eb-26b63b9f601e)
  
