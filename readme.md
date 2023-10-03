# AnyGate 공유기 분석
이 프로젝트는 `AnyGate`의 `WN5200Q`을 분석합니다.
## 하드웨어
CPU: `RTL8196E`

RAM: `16MB`

ROM: `4MB`

### 특이한 점
`WN5200Q`인데 내부적으로 `RG5200R`으로 모델네임을 사용함

## 소프트웨어
### UART
Baud Rate:`38400`

계정이름: `root`

비밀번호: 웹 UI 비밀번호와 동일(없는 경우 `admin`)

### 사용 소프트웨어
#### Linux
버전: `알 수 없음`

빌드 날짜: `알 수 없음`

라이선스: `GPLv2`

#### Busybox
버전: `1.13.4`

빌드 날짜: `2015-07-24 09:13:59 CST(미 중부 표준시)`

라이선스: `GPLv2`

#### WiFi Simple Config
버전: `2.11.1-wps2.0`

빌드 날짜: `2013.04.18-07:33+0000`

라이선스: `Closed Source`

설정 파일 버전: `1(Major).0(Minor)`

Realtek 제작

`CVE-2021-35393`에 취약(CVSS 3.x: **`9.8 CRITICAL`**/CVSS 2.0: **`10.0 HIGH`**)

**[PoC 공개](https://www.exploit-db.com/exploits/37169)**

#### Iapp
버전: `1.8`

빌드 날짜: `알 수 없음`

라이선스: `Closed Source`

Realtek 제작

[분석글(중국어)](https://blog.csdn.net/wgl307293845/article/details/117359675)

#### MiniIGD
버전: `1.08.1`

빌드 날짜: `2013.02.18-03:09+0000`

라이선스: `Closed Source`

Realtek 제작

`CVE-2014-8361`에 취약(CVSS 3.x: `N/A`/CVSS 2.0: **`10.0 HIGH`**)

**[PoC 공개](https://onekey.com/blog/advisory-multiple-issues-realtek-sdk-iot-supply-chain/)**

#### Dnrd
버전: `2.12.1`

빌드 날짜: `알 수 없음`

라이선스: `GPLv2`

Domain Name Relay Daemon

#### Linux-igd
버전: `알 수 없음`

빌드 날짜: `알 수 없음`

라이선스: `GPLv2`

#### IGMP Proxy
버전: `1.2`

빌드 날짜: `2015.07.24-01:15+0000`

라이선스: `GPLv2`

#### Boa
버전: `0.94.14rc21`
 
빌드 날짜: `Jul 24 2015 at 09`
 
라이선스: `GPLv2`
 
#### Lld2d
버전: `알 수 없음`

빌드 날짜: `알 수 없음`

라이선스: `알 수 없음`

마이크로소프트 제작

#### Timelycheck
버전: `알 수 없음`

빌드 날짜: `알 수 없음`

라이선스: `Closed Source`

Realtek 제작
