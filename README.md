<h1 align="left">
  안녕하세요! 서채건입니다.
</h1>

<p align="left">
  센서·모터 제어부터 Edge AI 서비스까지,<br>
  하드웨어와 소프트웨어가 함께 동작하는 시스템을 만드는 것에 흥미가 있습니다.<br>
  Arduino, Ubuntu, Rasbery pi 기반 프로젝트 경험을 바탕으로<br>
  임베디드와 AIoT 분야의 역량을 확장하고 있습니다.
</p>

## Tech Stack & Skills

<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/Hugging Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
  
  <br>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/Jetson Nano-000000?style=flat-square&logo=nvidia&logoColor=76B900">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
</p>

---

## Featured Projects

### 1. OpenVINO 기반 공장 컨베이어 자동화 시스템
- **[프로젝트 설명]** OpenVINO로 최적화된 AI 모델을 활용하여, 단일 컨베이어 벨트 위에서 3가지(정상, 부분불량, 완전불량) 유형의 제품을 실시간으로 선별하는 자동화 시스템을 개발했습니다.
- **[주요 역할]** **PM**을 맡아 전체 **코드 통합** 및 **하드웨어 연동** 테스트를 총괄했습니다. (Arduino, 컨베이어 제어 등)
- **[사용한 기술]** `Python`, `OpenVINO`, `Tkinter`, `Arduino`, `MySQL`, `PySerial`
- **[관련 링크]**  
  <a href="https://github.com/kccistc/intel-08/tree/main/Team2">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>
- **[영상]**  
  <a href="https://youtu.be/eomAWej_1nU">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 2. AI 기반 장문 텍스트 요약 서비스 (캡스톤 디자인)
- **[프로젝트 설명]** SKT의 KoBART 요약 모델을 활용하여 사용자가 입력한 장문의 텍스트를 핵심 내용으로 요약해주는 프로그램을 개발했습니다. Jetson Nano Orin 환경에서 AI 모델을 서빙하는 백엔드를 구축했습니다.
- **[주요 역할]** 
- **[사용한 기술]** `Python`, `FastAPI`, `Hugging Face`, `PyTorch`, `Jetson Nano`, `HTML/JS/PHP`
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/Long-article-summary">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>

### 3. CDS 센서 기반 태양광 패널 추적 시스템
- **[프로젝트 설명]** 8방위로 배치된 CDS 조도 센서 모듈을 통해 가장 밝은 빛을 감지하고, STM32 보드를 이용해 태양광 패널이 항상 태양을 향하도록 자동 회전하는 시스템을 구현했습니다.
- **[주요 역할]** **STM32 파트의 하드웨어 설계** 및 **펌웨어 프로그래밍**을 담당했습니다. (ESP8266 WiFi 통신, MySQL DB 데이터 저장, 패널 회전 로직 구현)
- **[사용한 기술]** `C`, `STM32`, `Arduino`, `MySQL`, `HTML`
- **[관련 링크]**  
  <a href="https://github.com/intel-edge-ai-sw-8/250826_2nd_miniproj_08"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtu.be/LcX8HYHIwDM">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 4. 차량 승하차 편의를 위한 자동 시트 조절기 (개인 프로젝트)
- **[프로젝트 설명]** 차량 승하차 편의를 위해, 차량 시동 상태와 기어 상태(P단)를 감지하여 시트 포지션을 자동으로 조절하는 하드웨어 시스템을 개발했습니다.
- **[주요 역할]** 개인 프로젝트 (회로 설계, Arduino 프로그래밍 및 차량 설치)
- **[사용한 기술]** `Arduino`, `Relay 2CH`
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/auto-seat-height-controller"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtu.be/nxEUnxjBgeY">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

---

## Education

* **목포대학교** 정보통신공학과 졸업 예정 (2026.02.)
* **대한상공회의소 서울기술교육센터** 인텔 AI 엣지 아카데미 교육 중 (2025.07. ~ 2026.01.)

---

## Connect with Me

E-MAIL: seo@chaegeon.com
