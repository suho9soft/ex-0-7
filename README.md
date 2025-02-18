# ex-0-7


ESP32 Wrover Module

![이미지 설명](https://github.com/suho9soft/ex-0-7/blob/main/61xa3vc2TYL._SL1010_.jpg)

![My Image](https://github.com/suho9soft/ex-0-7/blob/main/71D4E5DS-qL._SL1500_.jpg)

![Cute Cat](https://github.com/suho9soft/ex-0-7/blob/main/71d6%2BP4PUzL._SL1067_.jpg)

ESP2 Wrover Module Arduino 세팅  

ESP-32-C6-DEV-KIT-N8-M

![이미지 설명](https://github.com/suho9soft/ex-0-7/blob/main/%ED%99%94%EB%A9%B4%20%EC%BA%A1%EC%B2%98%202025-02-11%20235812.png)

아두이노 세팅 할때 

![My Image](https://github.com/suho9soft/ex-0-7/blob/main/%ED%99%94%EB%A9%B4%20%EC%BA%A1%EC%B2%98%202025-02-11%20235553.png)

waveshare Raspberry-Pi-Pico-2-W-M

![My Image](https://github.com/suho9soft/ex-0-7/blob/main/%ED%99%94%EB%A9%B4%20%EC%BA%A1%EC%B2%98%202025-02-13%20233753.png)

![Cute Cat](https://github.com/suho9soft/ex-0-7/blob/main/%ED%99%94%EB%A9%B4%20%EC%BA%A1%EC%B2%98%202025-02-13%20233837.png)

Raspberry Pi Pico 2W(M)를 아두이노(Arduino) 환경에서 프로그래밍하려면 다음과 같은 단계를 따라야 합니다.

✅ 준비물

라즈베리파이 피코 2W(M)

USB-C 케이블 (데이터 전송 가능)

PC(윈도우, 맥, 리눅스)

Arduino IDE 최신 버전

Raspberry Pi Pico용 보드 패키지 설치

📌 1. Arduino IDE 설치

아두이노 공식 웹사이트에서 Arduino IDE를 다운로드하여 설치합니다.

📌 2. Raspberry Pi Pico 보드 추가
Arduino IDE 실행
상단 메뉴 → "File(파일)" → "Preferences(환경설정)" 클릭
"Additional Boards Manager URLs(추가 보드 매니저 URL)" 항목에 다음 URL 추가
pgsql

복사
편집
https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json

**확인(OK)**을 눌러 저장

상단 메뉴 → "Tools(도구)" → "Board(보드)" → "Boards Manager(보드 매니저)" 실행

검색창에 "Raspberry Pi Pico/RP2040" 입력 후 설치

📌 3. Raspberry Pi Pico 2W(M) 연결

Pico 2W(M)의 BOOTSEL 버튼을 누른 상태에서 USB-C 케이블을 PC에 연결

"RPI-RP2"라는 드라이브가 나타나면 정상 연결

📌 4. Blink 예제 업로드 (LED 깜빡이기)

Arduino IDE 실행

상단 메뉴 → "File(파일)" → "Examples(예제)" → "01.Basics" → "Blink" 선택

상단 메뉴 → "Tools(도구)"에서 아래 설정 확인

Board(보드) → "Raspberry Pi Pico" 선택

Port(포트) → 자동으로 감지된 COM 포트 선택

CPU Speed(클럭 속도) → Default (125MHz)

업로드(▶) 버튼 클릭

📌 5. 업로드 오류 발생 시

포트가 안 보일 경우: Pico를 다시 연결 후 "BOOTSEL 버튼을 누르고 연결"

드라이버 문제: Raspberry Pi Pico 드라이버 수동 설치 필요




