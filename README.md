# team-jeongseongleejo
![header](https://capsule-render.vercel.app/api?type=waving)

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=300&section=header&text=Good%20to%20see%20you%20%F0%9F%A4%97)

# 🏠 AIoT Smart Home - Gesture Control System

서강대학교 컴퓨터공학과 **캡스톤디자인 I**  
**2팀 정성이조**  

손동작으로 제어하는 AIoT 스마트홈 시스템.  
카메라로 손동작을 인식하고, 가전기기를 제어하며, 상태를 대시보드로 확인할 수 있는 시스템을 제작하는 프로젝트입니다.

---

## 👥 팀 구성

- | 팀장 | 20221615 | 정다연 |
- | 팀원 | 20201590 | 성정후 |
- | 팀원 | 20221609 | 이충인 |
- | 팀원 | 20210428 | 정현정 |
- | 팀원 | 20201643 | 조영준 |
  
---

## 🧠 주요 기능

- Mediapipe 기반 손동작 인식
- MQTT 통신으로 아두이노 제어
- Uno R4 WiFi로 실제 기기 ON/OFF
- Firebase 연동 상태 저장
- 웹 대시보드로 상태 확인 + 로그 시각화
- 커스텀 제스처 등록 기능

---

## 🛠 기술 스택

- **손동작 인식**: Python, Mediapipe
- **IoT 제어**: Arduino Uno R4 WiFi, IR 송신 LED, 서보모터
- **통신 프로토콜**: MQTT
- **클라우드 연동**: Firebase Realtime Database
- **대시보드**: Flask + Flutter

---

## 📁 Repository 구조

```
Gesture_Recongnition/   # 손 제스처 인식 코드  
arduino_control/        # 아두이노 제어 코드  
gesture_server/         # 백엔드 서버
Application-Web/        # 대시보드(프론트)

```
