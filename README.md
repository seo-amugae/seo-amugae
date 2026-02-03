<h1 align="left">
  안녕하세요! 서채건입니다.
</h1>

<p align="left">
  센서·모터 제어부터 Edge AI까지, HW와 SW가 융합된 시스템을 만듭니다.<br>Arduino, Linux, Raspberry Pi 활용 경험을 바탕으로 Embedded & AIoT 역량을 넓혀가고 있습니다.
</p>

## 스킬

<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/Raspberry Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white">
  <img src="https://img.shields.io/badge/Jetson Nano-000000?style=flat-square&logo=nvidia&logoColor=76B900">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
</p>

---

## 프로젝트

### 1. OpenVINO 기반 공장 컨베이어 자동화 시스템 (🏅Intel Edge AI 프로젝트 경진대회 우수상)
- **[프로젝트 설명]** OpenVINO로 최적화된 AI 모델을 활용하여, 단일 컨베이어 벨트 위에서 3가지(정상, 부분불량, 완전불량) 유형의 제품을 실시간으로 선별하는 자동화 시스템을 개발했습니다.
- **[주요 역할]** 전체 코드 통합 및 하드웨어 연동 테스트를 총괄했습니다.
- **[사용한 기술]** `Python`, `OpenVINO`, `Tkinter`, `Arduino`, `MySQL`, `PySerial`
- **[수행 기간]** 2025. 09. 24. ~ 2025. 10. 22.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/Smartfactory">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>
- **[영상]**  
  <a href="https://youtu.be/eomAWej_1nU">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 2. ROS2 기반 사용자 추적 및 안내 스마트 카트
- **[프로젝트 설명]** ROS2 환경에서 UWB 통신을 활용하여 사용자를 실시간으로 추적(Following)하거나, 목적지까지 안내(Navigation)하는 자율주행 스마트 카트를 개발했습니다.
- **[주요 역할]** 하드웨어 플랫폼 커스터마이징 및 로드셀 센서 연동을 전담했습니다. TurtleBot3의 구조를 개조하여 센서와 모듈을 최적 배치했습니다.
- **[사용한 기술]** `Python`, `ROS2`, `Uvicorn`, `UWB`, `Load Cell`, `Qt`, `TurtleBot3`
- **[수행 기간]** 2025. 11. 20. ~ 2026. 01. 04.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/QT-CART">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>
- **[영상]**  
  <a href="https://youtu.be/Nhjt9ZBUZIo">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 3. OBD CAN 기반 운전 성향 분석 시스템 (🏅Intel Edge AI 프로젝트 경진대회 우수상)
- **[프로젝트 설명]** 차량 OBD-II 기반 CAN/UDS/OBD 통신으로 속도·조향각·브레이크·RPM 데이터를 수집하고, 위험 운전 행동(급가속/급제동/급조향 등)과 교통 흐름 방해 행동(저속 지속/평균 대비 저속 등)을 감점 요인으로 반영하여 운전 성향을 점수화하고 TFT 디스플레이에 실시간 시각화하는 시스템을 개발했습니다.
- **[주요 역할]** 하드웨어 회로 구성, CAN 통신 환경 구축, TFT/SD 모듈 연동, 차량 실환경 테스트를 담당했습니다.
- **[사용한 기술]** `Arduino`, `C/C++`, `MCP2515`, `CAN`, `UDS`, `OBD-II`, `Adafruit_ILI9341`, `SD`, `DS1302`
- **[수행 기간]** 2026. 01. 06. ~ 2026. 01. 19.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/driving-risk-flow-scoring">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>
- **[영상]**  
  <a href="https://youtu.be/YGfT60uI1hU">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 4. 차량 승하차 편의를 위한 자동 시트 조절기
- **[프로젝트 설명]** 차량 승하차 편의를 위해, 차량 시동 상태와 기어 상태(P단)를 감지하여 시트 포지션을 자동으로 조절하는 하드웨어 시스템을 개발했습니다.
- **[주요 역할]** 개인 프로젝트 (회로 설계, Arduino 프로그래밍 및 차량 설치)
- **[사용한 기술]** `Arduino`, `Relay 2CH`
- **[수행 기간]** 2024. 10. ~ 2025. 01.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/auto-seat-height-controller"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtu.be/nxEUnxjBgeY">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 5. Kernel Driver 기반 시계 & 불쾌지수 측정기
- **[프로젝트 설명]** Linux 기반 임베디드 시스템에서 DS1302 RTC, DHT11 센서, 로터리 엔코더, LED 바, I2C OLED를 연동하여 커널 드라이버가 하드웨어를 제어하고 유저 애플리케이션이 시계·온습도·불쾌지수(DI)를 멀티 페이지 UI로 표시하며 입력과 LED 시각화를 처리하는 스마트 시계 시스템을 개발했습니다.
- **[주요 역할]** 하드웨어 구성 및 테스트를 담당하여 센서·로터리 엔코더·LED 배선, 디바운싱 검증, 시스템 동작 안정성 및 통합 테스트를 수행했습니다.
- **[사용한 기술]** `C`, `Linux Kernel Driver`, `I2C`, `DS1302`, `DHT11`, `SSD1306`, `Rotary Encoder`
- **[수행 기간]** 2025. 12. 24. ~ 2025. 12. 29.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/Kernel-Weather-Clock">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white">
  </a>
- **[영상]**  
  <a href="https://youtu.be/SdUrgo2zXPU">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>
  <a href="https://youtu.be/pvqkJ--lABY">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 6. CDS 센서 기반 태양광 패널 추적 시스템
- **[프로젝트 설명]** 8방위로 배치된 CDS 조도 센서 모듈을 통해 가장 밝은 빛을 감지하고, STM32 보드를 이용해 태양광 패널이 항상 태양을 향하도록 자동 회전하는 시스템을 구현했습니다.
- **[주요 역할]** STM32 파트의 하드웨어 설계 및 펌웨어 프로그래밍을 담당했습니다. (ESP8266 WiFi 통신, MySQL DB 데이터 저장, 패널 회전 로직 구현)
- **[사용한 기술]** `C`, `STM32`, `Arduino`, `MySQL`, `HTML`
- **[수행 기간]** 2025. 08. 21. ~ 2025. 08. 25.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/Solarsense"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtu.be/LcX8HYHIwDM">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 7. 스마트 홈 환경 제어 IoT 시스템
- **[프로젝트 설명]** Arduino 기반 스마트 홈 IoT 시스템으로 실내·외 온습도, 가스, 조도, 강우, 창문 상태를 실시간으로 수집하고, 전기매트·보일러·자동 창문을 시간대·환경 조건·사용자 설정에 따라 자동 또는 수동으로 제어하는 스마트 홈 환경 제어 시스템을 구현했습니다.
- **[주요 역할]** 전체 시스템 설계 및 Arduino Mega 기반 펌웨어 개발을 담당했습니다. 센서 데이터 수집 로직, 히스테리시스 기반 난방 제어 알고리즘, 창문 리니어 액추에이터 제어 및 과부하 감지·복구 로직을 구현했으며, Ethernet Shield를 이용한 서버 통신과 EEPROM을 활용한 상태 유지 기능을 설계했습니다.
- **[주요 구현 기능]**
  - 전기매트·보일러 **히스테리시스 기반 항온 제어**
  - 실내·외 환경 조건에 따른 **자동 창문 개폐 및 환기 제어**
  - 창문 모터 **과부하 감지 및 자동 복구 로직**
  - 실시간 시계(RTC) 기반 시간·요일별 자동 제어
  - 원격 서버를 통한 상태 모니터링 및 수동 제어
- **[사용한 기술]** `Arduino`, `C/C++`, `Ethernet`, `DHT22`, `MQ-5`, `MQ-7`, `RTC DS3231`, `Relay`, `EEPROM`
- **[수행 기간]** 2022. 12. ~ 2023. 02.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/iot-project"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtube.com/shorts/GTiXDOWSPs4">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

### 8. AI 기반 장문 텍스트 요약 서비스
- **[프로젝트 설명]** SKT의 KoBART 요약 모델을 활용하여 사용자가 입력한 장문의 텍스트를 핵심 내용으로 요약해주는 프로그램을 개발했습니다. Jetson Nano Orin 환경에서 AI 모델을 서빙하는 백엔드를 구축했습니다.
- **[주요 역할]** AI 모델 서빙 및 백엔드 개발을 담당했습니다. (Jetson Nano 환경 구축, API 연동 및 웹 인터페이스 구현)
- **[사용한 기술]** `Python`, `FastAPI`, `Hugging Face`, `PyTorch`, `Jetson Nano`, `HTML/JS/PHP`
- **[수행 기간]** 2025. 03. 10. ~ 2025. 06. 20.
- **[관련 링크]**  
  <a href="https://github.com/seo-amugae/Long-article-summary"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"></a>
- **[영상]**  
  <a href="https://youtu.be/Dnco_6wpfG0">
  <img src="https://img.shields.io/badge/YouTube-Video-FF0000?style=flat-square&logo=youtube&logoColor=white">
  </a>

---

## 교육 사항

* **목포대학교** 정보통신공학과 졸업 예정 (2026.02.)
* **대한상공회의소 서울기술교육센터** 인텔 AI 엣지 아카데미 수료 (2025.07. ~ 2026.01.)

---

## 연락처

E-MAIL: seochaegeon1026@gmail.com

---

## Github

[![Metrics](./github-metrics.svg)](https://github.com/lowlighter/metrics)
