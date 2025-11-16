<div align="center">

# 🚌 BF Dream (Barrier-Free Dream)

### 임산부를 위한 스마트 배려석 알림 서비스

**기술로 만드는 더 따뜻한 대중교통 환경**

[![App Store](https://img.shields.io/badge/App%20Store-Coming%20Soon-blue?style=flat-square&logo=apple)](https://github.com/BFDream-AutoEver)
[![Google Play](https://img.shields.io/badge/Google%20Play-Coming%20Soon-green?style=flat-square&logo=google-play)](https://github.com/BFDream-AutoEver)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

</div>

---

## 📌 프로젝트 소개

**맘편한 이동**은 임산부의 73.1%가 겪는 대중교통 배려석 이용 불편함을 해결하기 위해 탄생했습니다.

GPS 기반 실시간 버스 정보와 블루투스 통신 기술을 활용하여, 임산부가 버스 배려석을 부담 없이 이용할 수 있도록 돕는 통합 솔루션입니다.

### 💡 핵심 가치

- **심리적 부담 해소**: 말로 양보를 부탁하는 부담감을 덜어드립니다
- **자연스러운 배려**: 승객들이 자연스럽게 배려를 실천할 수 있는 환경을 만듭니다
- **실시간 정보**: GPS 기반으로 가장 가까운 정류장과 버스 도착 정보를 제공합니다

---

## 🗂️ Repository 구성

### 📱 [BFDream-iOS](https://github.com/BFDream-AutoEver/BFDream-iOS)

**임산부 버스 배려석 알림 앱 (iOS)**

- **기술 스택**: Swift, SwiftUI, CoreLocation, CoreBluetooth
- **주요 기능**:
  - 실시간 버스 도착 정보 제공
  - 블루투스 기반 배려석 알림 전송
  - 서울시 공공데이터 API 연동

### 🤖 [BFDream-Android](https://github.com/BFDream-AutoEver/BFDream-Android)

**임산부 버스 배려석 알림 앱 (Android)**

- **기술 스택**: Kotlin, Jetpack Compose, Android SDK, Location Services, BLE
- **주요 기능**:
  - GPS 기반 정류장 자동 검색
  - 실시간 버스 노선 정보 조회
  - 배려석 알림 기기와 BLE 통신

### ⚙️ [BFDream-ESP32](https://github.com/BFDream-AutoEver/BFDream-ESP32)

**버스 배려석 알림 하드웨어 장치**

- **기술 스택**: Arduino (C/C++), ESP32, Bluetooth L
