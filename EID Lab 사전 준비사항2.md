# MSAL 실습을 위한 Github Codespace 생성 가이드
GitHub 계정 생성부터 Codespace 실행까지 단계별로 안내합니다.

---

## Step 1. GitHub Codespaces 소개 페이지 접속

[https://github.com/features/codespaces](https://github.com/features/codespaces) 에 접속하면 GitHub Codespaces 소개 페이지를 확인할 수 있습니다.  

**GitHub 계정이 있다면** `[무료로 시작하기]` 버튼이나 `[로그인(Sign in)]` 버튼을 통해 로그인을 합니다.  
**Github 계정이 없다면** `[가입(Sign up)]` 버튼을 통해 신규 가입을 시작합니다.

![Step 1 화면](./.srcs/msal.01.png)

---

## Step 1-1. GitHub 계정이 있는 경우

Github 로그인 후 오른쪽 상단의 `[Dashboard]` 버튼을 통해 Github 대시보드로 이동합니다. 이 후 `Step 3`에서 이어서 진행합니다.

![Step 1-1 화면](./.srcs/msal.01a.png)

---

## Step 2. GitHub 계정 생성

계정이 없는 경우 `[Create your free account]` 페이지에서 이메일, 사용자명 등을 입력하여 계정을 생성합니다.  
이메일은 반드시 메일 수신이 가능한 메일 주소를 사용해야 합니다. 등록한 이메일 주소로 Github 실행 코드가 전달됩니다.

![Step 2 화면](./.srcs/msal.02.png)

---

## Step 2-1. 소셜 계정으로 가입 (Google)

Google 이나 Apple의 계정이 있다면 `[Continue with Google]` 이나 `[Continue with Apple]`을 선택하여 소셜 계정으로 진행할 수 있습니다.

![Step 2-1 화면 1](./.srcs/msal.03.png)

GitHub 에서 Google 계정 정보(이름, 이메일)에 접근하는 것을 허용합니다. `[계속]` 버튼을 클릭합니다.

![Step 2-1 화면 2](./.srcs/msal.04.png)

---

## Step 2-2. 계정 정보 입력 및 인증

이메일과 사용자명이 자동 입력됩니다. 내용을 확인한 후 `[Create account]` 버튼을 클릭합니다.

![Step 2-2 화면 1](./.srcs/msal.05.png)

계정 생성 과정에서 상황에 따라 계정 보안 인증(CAPTCHA)이 필요할 수 있습니다. `[Visual puzzle]`을 선택하면 시각적 퍼즐 방식으로 인증합니다. 퍼즐은 상황에 따라 다른 퍼즐이 나타납니다.

![Step 2-2 화면 2](./.srcs/msal.06.png)

---

## Step 3. GitHub 대시보드 접속 확인

인증 완료 후 GitHub 대시보드(Home)로 진입됩니다. 이제 `Codespace`를 사용할 수 있습니다.

![Step 3 화면](./.srcs/msal.08.png)

---

## Step 4. Codespace 메뉴로 이동

좌측 사이드바에서 `[Codespaces]` 항목을 클릭합니다.

![Step 4 화면 1](./.srcs/msal.10.png)

![Step 4 화면 2](./.srcs/msal.11.png)

Codespace 메인 페이지가 열립니다.  
다음으로 하단의 템플릿 중 `[.NET]`을 확인한 후 `[Use This Template]` 버튼을 통해 `.NET` 개발용 Codespace를 생성합니다.

![Step 4 화면 3](./.srcs/msal.12.png)

---

## Step 5. Codespace 실행 완료

일정 시간 후 Codespace가 생성되면 브라우저에서 `VS Code` 환경이 열립니다.  
이제 터미널, 파일 탐색기, 에디터를 통한 실습을 진행할 수 있습니다.

![Step 5 화면](./.srcs/msal.13.png)
