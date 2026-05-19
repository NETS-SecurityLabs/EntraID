# MSAL 실습을 위한 Github Codespace 생성 가이드
GitHub 계정 생성부터 Codespace 실행까지 단계별로 안내합니다.

---

## Step 1. GitHub Codespaces 소개 페이지 접속

`https://github.com/features/codespaces` 에 접속하면 GitHub Codespaces 소개 페이지를 확인할 수 있습니다. GitHub 계정이 **있다면** `[무료로 시작하기]` 버튼을 통해 시작하거나 `[로그인(Sign in)]` 버튼을 통해 시작할 수 있습니다.

![Step 1 화면](.srcs\msal.01.png)

---

## Step 1-1. GitHub 계정이 있는 경우

오른쪽 상단의 `[Dashboard]` 버튼을 통해 Codespace 대시보드로 이동합니다. 이후 `Step 5`에서 이어서 진행합니다.

![Step 1-1 화면](.srcs\msal.01a.png)

---

## Step 2. GitHub 계정 생성

계정이 없는 경우 `[Create your free account]` 페이지에서 이메일, 사용자명 등을 입력하여 계정을 생성합니다.

![Step 2 화면](.srcs\msal.02.png)

---

## Step 3. Google 계정으로 로그인 (소셜 로그인)

Google 계정이 있다면 `[Continue with Google]`을 선택하여 Google 계정으로 진행할 수 있습니다.

![Step 3 화면 1](.srcs\msal.03.png)

GitHub가 Google 계정 정보(이름, 이메일)에 접근하는 것을 허용합니다. `[계속]` 버튼을 클릭합니다.

![Step 3 화면 2](.srcs\msal.04.png)

---

## Step 4. 계정 정보 입력 및 인증

이메일과 사용자명이 자동 입력됩니다. 내용을 확인한 후 `[Create account]` 버튼을 클릭합니다.

![Step 4 화면 1](.srcs\msal.05.png)

계정 생성 과정에서 상황에 따라 계정 보안 인증(CAPTCHA)이 필요할 수 있습니다. `[Visual puzzle]`을 선택하면 시각적 퍼즐 방식으로 인증합니다. 퍼즐은 상황에 따라 다른 퍼즐이 나타납니다.

![Step 4 화면 2](.srcs\msal.06.png)

---

## Step 5. GitHub 대시보드 접속 확인

인증 완료 후 GitHub 대시보드(Home)로 진입됩니다. 이제 레포지토리 생성 및 `Codespace`를 사용할 수 있습니다.

![Step 5 화면](.srcs\msal.07.png)

---

## Step 6. 새 레포지토리 생성

Codespace를 사용하려면 레포지토리가 필요합니다. 우측 상단 `[+]` 버튼 또는 좌측 패널의 `[Create repository]`를 클릭합니다. `Repository name`을 입력하고(예: `msaldemo`), `Visibility`를 선택한 후 `[Create repository]`를 클릭합니다.

![Step 6 화면 1](image010.gif)

레포지토리가 생성되면 레포지토리 메인 페이지가 표시됩니다.

<!-- 문서에는 두 번째 이미지가 비어 있어 파일명을 확인할 수 없었습니다 -->

---

## Step 7. Codespaces 메뉴로 이동

좌측 사이드바에서 `[Codespaces]` 항목을 클릭합니다.

![Step 7 화면 1](image011.gif)

![Step 7 화면 2](image012.gif)

Codespaces 메인 페이지가 열립니다. 다음으로 하단의 템플릿 중 `[.NET]`을 선택하여 `.NET` 개발용 Codespace를 생성합니다.

![Step 7 화면 3](image013.gif)

---

## Step 8. Codespace 실행 완료

Codespace가 생성되면 브라우저에서 `VS Code` 환경이 열립니다. 터미널, 파일 탐색기, 에디터를 모두 사용할 수 있습니다.

![Step 8 화면](image014.gif)
