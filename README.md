# WASDPad for LostArk v0.7.125
## ◈ 목적 ◈
- 키보드의 WASD키 신호를 XBox360 컨트롤러 신호로 에뮬레이션 해주는 프로그램.
- LostArk의 캐릭터 이동을 마우스가 아닌 키보드의 WASD키로 가능.

## ◈ 사용 라이브러리 ◈
1. Interception 
   - Site ▶ https://github.com/oblitum/Interception
   - 키보드, 마우스 신호를 받기 위한 라이브러리.
2. ScpVBus
   - Site ▶ https://github.com/nefarius/ScpVBus
   - XBox360 컨트롤러 신호를 발생시키기 위한 에뮬레이터.

## ◈ 설치 순서 ◈
1. Interception 드라이버 설치
   - Install\Interception\install.bat 파일을 관리자 권한으로 실행한다.
   - (직접 다운로드: https://github.com/oblitum/interception/releases)
2. ScpVBus 드라이버 설치
   - Install\ScpVBus\install.bat 파일을 관리자 권한으로 실행한다.
   - (직접 다운로드: https://github.com/shauleiz/vXboxInterface/releases)
3. 재부팅한다.

## ◈ 사용 방법 ◈ 
    [ 모드 공용 ] ☞ 마우스 모드와 패드 모드에 상관없이 항상 사용가능한 단축키.
    → 프로그램 종료 : Alt + Q
    → 일시 정지 : Alt + Z (모든 기능을 일시적으로 정지.)
    → 모드 전환 : CapsLock (마우스 모드와 패드 모드 사이를 전환.)
    → 상호 작용 : MButton (인게임 G버튼, 드래그시 연타효과.)
    → 확대 축소 : Ctrl + Scroll or Alt + Scroll (패드 모드에선 필수.)
    → 팅김 방지 : Ctrl + P (30초마다 인벤토리창을 토글, LostArk가 비활성화 상태라도 작동.) 
        (** ↑ 팅김 방지 기능은 관리자 권한이 필요합니다.)
    
    [ 마우스 모드 ] ☞ 기존 컨트롤 방법에 익숙한 유저를 위한 모드.
    → 달리기 : 더블 클릭 (마우스 방향으로 자동 달리기.)
    → 말타기 : 자동 달리기 중에 Wheel Up
    → 내리기 : 자동 달리기 중에 Wheel Down
    → 물약 먹기 : Wheel Down (자동 달리기 중에는 작동하지 않는다.)

    [ 패드 모드 ] ☞ WASD키로 캐릭터를 움직이고 마우스로 스킬을 사용하기 위한 모드.
    → 이동 : WASD 키
    → 달리기 : Q (마우스 방향으로 자동 달리기.)
    → 말타기 : E
    → 내리기 : RButton
    → 마우스 : Alt + Mouse (Alt키를 누르면 아래 스킬 대신 마우스로 사용 가능.)
    → 물약 먹기 : F
    → 기본 공격 : MButton (상호 작용 기능 겸용, 상호 작용만 원할 경우 Shift + MButton)
    → 스킬 1(Q) : LButton
    → 스킬 2(W) : Wheel Up
    → 스킬 3(E) : Wheel Down
    → 스킬 4(R) : RButton
    → 스킬 5(A) : Shift + LButton
    → 스킬 6(S) : Shift + Wheel Up
    → 스킬 7(D) : Shift + Wheel Down
    → 스킬 8(F) : Shift + RButton

## ◈ 주의 사항 ◈ 
    ※ 패드 모드 사용시 주의점 : 패드 모드는 마우스의 모든 버튼을 공격 스킬에 사용하므로 일반적인 마우스의 사용에 불편함이 따른다. 따라서 전투 중이 아닐 경우에는 마우스 모드를 사용하거나 일시 정지를 통해서 마우스를 사용하는게 좋다. 단, 패드 모드에서 급하게 마우스를 사용하기 원한다면 Alt키를 누르고 마우스를 사용하면 된다.

### 연락처
- 질문이 있을 경우 메일(whitesnake@uzoo.in)로 연락주세요.

### 라이센스
- This software is licensed under CC-BY-NC-ND license. © 2018 whitesnake contributors
- 이 프로그램은 개인에게만 무료로 제공이 되며, 상업적 또는 영리적 이용은 제한됩니다.