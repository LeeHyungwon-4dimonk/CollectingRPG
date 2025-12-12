# CollectingRPG
수집형 RPG 장르의 오토배틀러 게임으로, 캐릭터 수집, 강화, 소환을 통한 오토배틀을 중심으로 시스템을 설계하였습니다.

This repository is a **fork of the original team project**, reorganized for portfolio purposes.

## 시연 영상

https://github.com/user-attachments/assets/8e91025f-fbdf-4bf0-b4f8-9554d5f7d6c9

* 게임 다운로드 경로 : https://play.google.com/store/apps/details?id=com.CollectingRPG&hl=ko

<br>

## 📌 Project Overview

| 항목 | 내용 |
|------|------|
| **프로젝트 유형** | 팀 프로젝트 (12인, 기획 6인 클라 6인) |
| **장르** | Collecting RPG |
| **엔진** | Unity |
| **언어** | C# |
| **개발 방식** | Git Flow / Feature Branch |
| **진행 기간** | *2025-08-18 ~ 2025-10-16* |
| **팀 규모** | *12명* |
| **개인 역할** | Gameplay & System Programming |


## 🧑‍💻 My Contributions

### 🎯 Gameplay & Core Systems
- 캐릭터 **편성** 시스템 구현  
- **캐릭터/마법석 뽑기** 시스템 구현  
- 데이터베이스 연동형 **강화 시스템** 제작  
- 일일 초기화, 상점 로직, 광고 기반 소환 등 **게임 루프 핵심 로직 개발**  
- 인게임 **증강(Augment) 시스템** 구현

### 🎨 UI & UX
- 로비 화면 UI 개발
- 캐릭터 선택 애니메이션 구현

### 🔄 Backend Integration
- 서버/DB 연동 로직 작성
- 데이터 요청 & 응답 기반 시스템 구성
- 게임 내 정보 로딩/저장/갱신 흐름 설계

<br>

## 🛠 Tech Stack

### ✔ Engine & Language
- Unity 2022 / C#

### ✔ Tools & Libraries
- **UniTask** (비동기 처리)
- Git / GitHub

### ✔ Workflows
- Feature Branch 기반 브랜치 전략  
- 코드 리뷰 및 팀 협업 경험  

<br>


## 📁 My Code Overview

하기 경로에 제가 직접 구현한 스크립트들이 정리되어 있습니다.

Assets/WorkSpace/LHW/Scripts/

### 🔹 캐릭터 편성 시스템
- TeamOrganizeManager.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/Lobby/CharacterCompositionUI/`

### 🔹 캐릭터 편성 연출
- SelectedCharacterUnit.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/Lobby/CharacterCompositionUI/`

### 🔹 캐릭터 및 마법석 뽑기 시스템
- RandomGachaSystem.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/Lobby/RandomGacha/`

### 🔹 캐릭터 및 마법석 강화 시스템
- UpgradeUnitData.cs
- MagicStoneUpgradeUnit.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/Lobby/Upgrade/`

📂 Path: `Assets/WorkSpace/LHW/Scripts/Temp/SO/`

### 🔹 게임 내 시간 기반 콘텐츠 관리 매니저
- TimeManager.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/Manager/`

### 🔹 파이어베이스 데이터베이스 연동(Unitask 활용)
- CharDB.cs
- MagicStoneDB.cs
- TimeDB.cs

📂 Path: `Assets/WorkSpace/LHW/Scripts/DB/`
