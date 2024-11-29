# 하이브리드 포트폴리오

### 안드로이드 개발 환경 구축
- JDK 설치
- 아파치 앤트 설치
- gradle 설치
- 안드로이드 개발 도구인 Android SDK 설치
- 안드로이드 플랫폼 패키지 추가 설치
- 환경 변수 설정

### 코르도바 프로젝트 개발 환경 구축

- 노드.js 구축
- 폰갭 설치
- 코르도바 설치

---

### Install
1. [JDK 설치](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
   - Java SE 8u241
2. [아파치 앤트 설치](http://ant.apache.org/bindownload.cgi)
   - 1.10.7 .zip archive: apache-ant-1.10.7-bin.zip 다운로드
3. [그래들 설치](https://gradle.org/install/)
   -v6.1.1 Jan 24, 2020 Download: binary-only
4. [안드로이드 스튜디오 설치](https://developer.android.com/studio/)
   ※SDK Manager 
		    SDK Tools
			     Android SDK Tools
			     Android SDK Platform-tools
			     Android SDK Build-tools
			     Google Respository
			     Google USB Driver
			     Intel x86 Emulator Accelerator(HAXM installer)
			     NDK - un check

5. 환경변수 설정
   JAVA_HOME : C:\Program Files\Java\jdk1.8.0_45
   ANDROID_SDK_ROOT : C:\Users\cs\AppData\Local\Android\Sdk


   PATH			C:\Program Files\Java\jdk-10.0.2\bin
		      	C:\hybrid\gradle-6.1.1\bin
		      	C:\hybrid\apache-ant-1.10.5\bin
		      	C:\Users\cs\AppData\Local\Android\Sdk\tools
	      		C:\Users\cs\AppData\Local\Android\Sdk\platform-tools
	      		C:\Users\cs\AppData\Local\Android\Sdk\build-tools

6. 코르도바(폰갭) CLI 설치
7. [노드.js 설치](https://nodejs.org/ko/)
   - 시작 - Node.js - Node.js command prompt
     >cd \
     
     >md hybridProj
     
     >cd hybridProj
     
     >npm install -g phonegap
     
     >npm update -g phonegap
     
     >npm install -g cordova
     
     >npm update -g cordova
     
     >cordova -v
     
     >cordova create test com.example.test testApp -d
     
     >cd test
     
     >dir
     
     >cordova platform add android
     
     >dir platform

  - 사용하고 있는 스마트폰 USB 드라이버 파일 다운로드
    환경설정 - 개발(개발자옵션) - USB 디버깅
    스마트폰 연결 
	       연결모드를 "저장소를 PC에 연결" 모드를 선택하면 안됨
	       'USB 사용용도' 옵션에서 "미디어 파일 전송(MTP 연결)" 모드가 아닌 다른 모드

    >cordova run android --list


  - 가상 단말기 실행
    >cordova emulate android

  - 실물 단말기
    >cordova run android
    
---
