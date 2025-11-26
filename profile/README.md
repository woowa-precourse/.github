<div align="center">

<img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/logo.png" width="120">

# 🌤️ 날씨의 코디 👕
**우아한테크코스 openCourse: 제한 협업 미션**

오늘의 날씨에 맞는 코디 추천 </br>  
2025.11.17 ~ 2024.11.25

<br/>

</div>

<div>  

  <div style="flex: 1; margin-right: 20px;">
    <h2>📜 Contents</h2>
      1. <a href="#-서비스-화면">서비스 화면</a> </br> 
      2. <a href="#-주요-기능">주요 기능</a> </br> 
      3. <a href="#%EF%B8%8F-개발-환경">개발 환경</a> </br> 
      4. <a href="#-시스템-아키텍처">시스템 아키텍처</a> </br> 
      5. <a href="#-기술-특이점">기술 특이점</a> </br> 
	    6. <a href="#-팀원-소개">팀원 소개</a> </br> 
  </div>  
  </br>   

  <div>  
    <h2>🌤️👕 날씨의 코디 개요 </h2></br>     
    
“오늘 기온에 뭐 입지?” <br>
기온별로 적절한 옷을 고르는 건 늘 고민거리지만, 기존 코디 앱은 내가 가지고 있지 않은 옷으로 코디를 추천해 구매를 유도하는 경우가 많다. <br>
이 프로젝트는 내가 실제로 가진 옷들만을 기반으로, 기온별 맞춤 코디를 자동으로 보여주는 개인화된 코디 앱이다. <br>
       
   <h2> 🎯 기획배경  </h2>
      - 오늘 기온에 어떤 옷을 입어야 할지 종종 헷갈림 <br>
      - 기존 코디 앱은 보유하지 않은 옷을 기반으로 추천해 실효성이 낮음 <br>
      - 실제로 내가 가진 옷들을 기반으로 기온에 맞는 코디 조합을 직접 만들고 저장하고 싶었음 <br>
      - 이를 위해 내 옷장 기반·기온 기반 코디 추천 앱을 기획 <br>

   
  </div>

</div>  

</br>   
	
# 📱 서비스 화면

| 옷 페이지 (clothes) | 코디 페이지 (cody) |
|---------------------|---------------------|
| <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/clothes.jpg" width="200"> | <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/cody.jpg" width="200"> |

| 코디 추가 페이지 (codyadd) | 코디 상세 페이지 (codydetail) |
|----------------------------|-------------------------------|
| <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/codyadd.jpg" width="200"> | <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/codydetail.jpg" width="200"> |

| 날씨별 옷 추천 페이지 (home) | 날씨 지역 선택 페이지 (region) |
|-----------------------------|-------------------------------|
| <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/home.jpg" width="200"> | <img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/region.jpg" width="200"> |



## 📌 주요 기능

1. 지역별 날씨 연동
   
<img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Atmosphere.png" width="150"><img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Clear.png" width="150"><img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Clouds.png" width="150"><img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Rain.png" width="150"><img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Snow.png" width="150"><img src="https://raw.githubusercontent.com/woowa-precourse/woowa-android/main/images/Thunderstorm.png" width="150">

  - Weather API를 활용해 내 위치의 현재 기온을 메인 화면에 크게 표시
	- 기온에 따라 사용자 맞춤 코디 자동 추천

2. 내 옷장 관리
  - 사용자가 옷을 직접 촬영해 앱에 등록
	- 이미지 업로드 시 자동 누끼 제거 기능으로 배경을 제거한 상태로 저장
	- 옷 등록 과정에서 사용자 정의 카테고리 선택

4. 코디 조합 기능
  - 등록한 옷들을 자유롭게 조합해 여러 코디를 저장
	- 기온별로 코디 다양하게 등록 가능

5. 기온 기반 코디 추천
  - 메인 페이지에서 오늘 기온에 맞는 코디 목록 자동 출력
	- 사용자가 실제 보유한 옷으로 구성되어 현실성 높은 추천 제공

## ✨ 기술 특이점
  - 

<br/>   
<br/>   


## 🖥️ 개발 환경

### 🎒 Backend
<div> 
	<img src="https://img.shields.io/badge/Kotlin-B916DD?style=for-the-badge&logo=Kotlin&logoColor=white">
	<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=Spring-Boot&logoColor=white">
	<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white">
	<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black">
</div>
<br/>

### 📱 Android
<div>
	<img src="https://img.shields.io/badge/Kotlin-B916DD?style=for-the-badge&logo=Kotlin&logoColor=white">
	<img src="https://img.shields.io/badge/JetpackCompose-6DB33F?style=for-the-badge&logo=Jetpack-Compose&logoColor=white">
</div>
<br/>

### 🗂️ DB
<div>
	<img src="https://img.shields.io/badge/PostgreSQL-306091?style=for-the-badge&logo=PostgreSQL&logoColor=white">
	<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">	
</div>
<br/>


### 🌐 Server
<div>
	<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white">
	<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
</div>
<br/>

<br/>

<div>    
	
## 💫 시스템 아키텍처

<img width="1039" height="483" alt="Image" src="https://github.com/user-attachments/assets/91af1723-ee3d-4d8e-969e-bfa3e7d1475b" />

</div>  

<br/>

<div>

## 📄 API 명세서
[날씨의코디_API명세서_v1.pdf](../날씨의코디_API명세서v1.pdf)

</div>

<br/>     

<div>

### ✨ ER Diagram
<img width="847" height="472" alt="Image" src="https://github.com/user-attachments/assets/aca3dbf1-d42e-4dfb-8e06-780ecbed841e" />
<!-- <img width="100%" alt="erd" src="https://github.com/user-attachments/assets/9de9eeba-8fba-4930-a9a1-8b2b3bfc3844" ><br> -->
</div>

## ✨ 추후 고도화 
- 

<br/>   
 

## 👥 팀원 소개

<div>
<table>
    <tr>
        <td align="center">
        <a href="https://github.com/parkdu7">
          <img src="https://avatars.githubusercontent.com/u/59389436?v=4" width="120px;" alt="parkdu7">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/syeony">
          <img src="https://avatars.githubusercontent.com/u/101008357?v=4" width="120px;" alt="syeony">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/XIOZ119">
          <img src="https://avatars.githubusercontent.com/u/63907578?v=4" width="120px;" alt="XIOZ119">
        </a>
      </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/parkdu7">
        박승균
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/syeony">
        오승연
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/XIOZ119">
        홍시은
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
        MOBILE
    </td>
    <td align="center">
      MOBILE
    </td>
    <td align="center">
      BE
    </td>
  </tr>
</table>
</div>
