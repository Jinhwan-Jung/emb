# EMB (Electronics Motor Brake)

10BASE-T1S 학습할 수 있는 평가 보드
- MCU
  - NUCLEO-H723ZG : STM32F 저가형 모델
  - STM32H7B3I-DK : STM32H 고급형 모델
 
- PHY 모듈
  - TI DP83TT510EVM
  - Microchip LAN8670 (https://www.microchip.com/en-us/product/LAN8670)
    - EVB-LAN8670-RMII (https://www.microchip.com/en-us/development-tool/EV06P90A)
    - EVB-LAN8670-USB  (https://www.microchip.com/en-us/development-tool/EV08L38A) 
---
- LAN
  - Local Area Network : 근거리 통신망
  - 여러 시스템이 하나의 네트워크 장비(공유기)에 연결된 네트워크
- WAN
  - Wide Area Network : 광역 통신망
  - LAN이 하나 이상 연결된 통신망
 

- Protocol
  - 가까운 거리에서 데이터 교환 프로토콜
    - Ethernet
  - 먼 거리에서 데이터 교환 프로토콜
    - IP(Internet Protocol)
  - 특정 컴퓨터에서 실행중인 프로그램에 데이터를 전달
    - TCP(Transmission Control Protocol)
    - UDP(User Datagrame Protocol)
---
#### 네트워크 모델
- TCP/IP 모델
  - 4단계 : 응용
  - 3단계 : 전송
  - 2단계 : 인터넷
  - 1단계 : 네트워크 엑세스
- OSI 7 Layer 모델 -> TCP/IP보다 세부환 된 표준
  - 7단계 : 응용
  - 6단계 : 표현
  - 5단계 : 세션
  - 4단계 : 전송
  - 3단계 : 전송네트워크
  - 2단계 : 데이터링크
  - 1단계 : 물리

---
* PLCA (Physcal Layer Collision Avoidance)
