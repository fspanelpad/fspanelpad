# FS PanelPad

Control Microsoft Flight Simulator 2024 cockpit switches from an Android tablet.
안드로이드 태블릿으로 MSFS 2024 조종석 스위치를 조작하는 앱입니다.

This repository only hosts the **PC bridge** downloads. 이 저장소는 **PC 브리지** 내려받기 전용입니다.

## 내려받기 / Download

👉 **[최신 버전 받기 / Latest release](https://github.com/fspanelpad/fspanelpad/releases/latest)**

## 사용 방법

1. `FSPanelPadBridge-<버전>-win-x64.zip` 을 받아 압축을 풉니다.
2. MSFS 2024가 켜진 PC에서 `FSPanelPadBridge.exe` 를 더블클릭합니다.
   - 처음 실행할 때 "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행** 을 누르세요.
   - Windows 방화벽 창이 뜨면 **허용** 을 누르세요. 그래야 태블릿이 PC에 붙습니다.
3. 검은 창에 나오는 **PC 주소**(예: `192.168.0.10`)를 태블릿 앱의 연결 화면에 입력합니다.
4. 비행하는 동안 검은 창은 켜 두세요.

태블릿과 PC는 같은 와이파이(공유기)에 연결되어 있어야 합니다.

## How to use

1. Download `FSPanelPadBridge-<version>-win-x64.zip` and unzip it.
2. On the PC running MSFS 2024, double-click `FSPanelPadBridge.exe`.
   - If "Windows protected your PC" appears, click **More info → Run anyway**.
   - If Windows Firewall asks, click **Allow** so the tablet can reach the PC.
3. Type the **PC address** shown in the window into the tablet app's connect screen.
4. Keep the window open while you fly.

The tablet and the PC must be on the same Wi-Fi network.

## 확인용 SHA-256 / Checksums

Each release lists `SHA256SUMS.txt`. 각 릴리스에 `SHA256SUMS.txt` 가 있습니다.

## Third-party software

The bridge includes [node-simconnect](https://github.com/EvenAR/node-simconnect) (LGPL-3.0-or-later) and other open-source libraries. See `THIRD-PARTY-NOTICES.txt` in the download.
