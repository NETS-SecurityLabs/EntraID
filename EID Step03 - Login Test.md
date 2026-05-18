## Salesforce 로그인
  1. [EID Lab 사전 준비사항](EID%20Lab%20사전%20준비사항.md) 참고하여 접근 도메인 및 관리자 계정 확인
  2. 브라우저에서 생성된 Salseforce URL로 접근(`https://orgfarm-<random key>-dev-ed.develop.my.salesforce.com/`)
  3. 관리자 계정을 입력하여 로그인

## 로그인 테스트 사용자 추가
  1. 우측 상단의 `설정(기어 아이콘)` 메뉴를 클릭한 후 `설정-현재 앱 설정` 메뉴 선택
  2. 새로 열련 창의 좌측 메뉴에서 `관리` > `사용자` > `사용자` 선택
  3. `새 사용자` 버튼 클릭
  4. 다음 항목 입력
        - 성: `<name>`labuser01
        - 별칭: `<name>`labuser01
        - 이메일: `인증 코드를 받을 수 있는 개인 또는 업무용 메일`
        - 사용자 이름: `<name>`labuser01@lab.castanets.io
        - 별명: `<name>`labuser01
        - 사용자 라이센스: Chatter Free
        - 프로필: Chatter Free User
  5. '저장' 버튼 클릭하여 새 사용자 등록

## Secret/inPrivate 모드로 새 브라우저 실행
  1. Salseforce 접근 URL 입력
  2. 로그인 화면에서 `로그인 정보 Entra ID로 로그인` 버튼 클릭
  3. Entra ID 로그인 화면에서 `<name>`labuser01@lab.castanets.io 사용자로 로그인
  4. 로그인 성공되면 Salseforce 화면 표시됨
